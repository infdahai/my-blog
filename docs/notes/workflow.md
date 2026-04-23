---
title: My Knowledge Workflow
description: Zotero × Obsidian × MkDocs × GitHub Pages 全流程参考
tags: [meta, workflow]
---

# My Knowledge Workflow

> 写于 2026-04-23。这套工作流的目的：**一个地方写、一处发布、多机同步**。

## 全景图

```
            ┌─────────────────┐
            │  Zotero (Mac)   │  PDF 阅读 + 高亮 + 批注
            │  ~/Zotero/      │  sqlite 本地（防 iCloud 损坏）
            │                 │  Linked PDFs → iCloud Zotero_Attachments
            └────────┬────────┘
                     │ Zotero Integration 直连 HTTP API
                     ▼
            ┌─────────────────┐
            │ Obsidian Vault  │  唯一写作入口
            │ ~/workspace/    │  docs/notes/   零散想法
            │  code/my-blog/  │  docs/papers/  论文笔记（自动生成）
            │                 │  docs/posts/   博客正文
            └────────┬────────┘
                     │ Obsidian Git auto-commit + auto-push 每 10 min
                     ▼
            ┌─────────────────┐
            │  GitHub Repo    │  infdahai/my-blog
            └────────┬────────┘
                     │ GitHub Actions: mkdocs build → deploy-pages
                     ▼
            ┌─────────────────┐
            │  GitHub Pages   │  https://infdahai.github.io/my-blog/
            └─────────────────┘
```

## 三个高频场景

### 场景 1 ── 写一条想法 / 知识沉淀

1. Obsidian 打开 `docs/notes/` 任意目录
2. 新建文件，文件名 kebab-case，比如 `vla-action-tokens.md`
3. 顶部加 frontmatter：
   ```yaml
   ---
   title: VLA 模型的 action token 化
   tags: [embodied-ai, vla]
   ---
   ```
4. 写内容 → 保存。
5. 不用管推送，**Obsidian Git 后台每 10 分钟 auto-commit + auto-push**。
6. 5-10 分钟后访问 `https://infdahai.github.io/my-blog/notes/vla-action-tokens/` 即可看到。

### 场景 2 ── 加一篇论文笔记

1. Zotero 中打开 PDF → 划黄色高亮 / 写 Note
2. 切回 Obsidian → `Cmd+P` → 搜 `Zotero Integration: Insert notes into current document`
3. 选 **Paper Note** format → 弹出文献搜索框 → 选目标论文
4. 自动生成 `docs/papers/{citekey}.md`：
    - YAML frontmatter（title / authors / year / DOI / 标签）
    - 正文骨架（TL;DR / Problem / Method / Results / My Notes）
    - **所有高亮 + 批注**塞进 `Highlights & Annotations` 段落
    - 截图存到 `docs/images/{citekey}/` 并自动嵌入
5. 想再补高亮？回 Zotero 多划几条 → 在同一篇笔记上再触发一次 → **只追加新内容**，不重复（靠模板里 `{% persist %}` + `lastImportDate`）

### 场景 3 ── 写一篇博客文章

1. Obsidian 在 `docs/posts/` 下新建 `2026/04/24-标题.md`
2. 顶部 frontmatter：
   ```yaml
   ---
   date: 2026-04-24
   categories: [System Design]
   tags: [observability]
   ---
   ```
3. 写正文。本地预览：终端跑 `~/workspace/code/my-blog/.venv/bin/mkdocs serve` → http://127.0.0.1:8000
4. 保存即推 → 几分钟后博客首页自动更新。

## 关键命令速查

```bash
# 进项目
cd ~/workspace/code/my-blog

# 本地预览
.venv/bin/mkdocs serve              # http://127.0.0.1:8000

# 本地严格构建（CI 之前自检）
.venv/bin/mkdocs build --strict

# 立即触发部署（不等 push 触发）
gh workflow run pages.yml --repo infdahai/my-blog

# 看部署状态
gh run list --repo infdahai/my-blog -L 3
gh run watch --repo infdahai/my-blog

# 手动 commit + push（不想等 10 min）
git add -A && git commit -m "msg" && git push
# 或在 Obsidian 里 Cmd+P → "Obsidian Git: Commit all changes"
```

## 多机使用（未来 Mac B）

1. Mac B 装 Zotero、Obsidian
2. `git clone git@github.com:infdahai/my-blog.git ~/workspace/code/my-blog`
3. Obsidian → Open folder as vault → 选上述路径
4. **插件已经在仓库里了**，进 Settings → Community plugins → enable Obsidian Git / Zotero Integration 即可
5. Zotero 多机同步另一回事，看 `docs/notes/` 里另开的笔记。

## 防坑须知

| 坑 | 说明 |
|---|---|
| Zotero dataDir **不要**放 iCloud | sqlite 锁不被 iCloud 尊重，多机大概率损坏。当前已回归 `~/Zotero/`，只 PDF 走 iCloud。 |
| `*.pdf` / `*.mp4` 在 `.gitignore` | Git 仓库轻量化，二进制大文件别误传。 |
| `.obsidian/workspace.json` 已忽略 | 防 MBP / Air 互相覆盖窗口布局。 |
| `docs/zotero/` 排除出 site 构建 | 见 `mkdocs.yml` 的 `exclude_docs`。 |
| BBT / ZotMoov 版本必须匹配 Zotero 7 | BBT 7.x 给 Zotero 7；BBT 9.x 给 Zotero 8 beta。装错会拒绝安装。 |
| Pages 需 public repo + Pages source = Actions | 已配好。如果以后 Pages 没更新，先看 Actions 是否成功。 |

## 故障排查

- **博客没更新** → `gh run list -R infdahai/my-blog`，看最近一次 workflow 是否 success；点开看哪一步失败
- **Obsidian Git push 失败** → 命令面板 → `Obsidian Git: Open status bar` 看错误；通常是 git remote 凭证问题 → 终端 `git push` 一次让 SSH 缓存
- **Zotero 启动崩溃** → 按住 `Option` 启动 → 弹窗勾 `Disable all add-ons` → 进入后逐个启用插件定位元凶
- **某篇 paper 笔记里高亮不导入** → Zotero Integration 设置里 `betterBibTexCitekey: true` 必须开；BBT 必须给该条目分配过 citekey（Zotero 中 Item → Extra 字段应能看到 `Citation Key: xxx`）

## 相关链接

- Repo: <https://github.com/infdahai/my-blog>
- Pages: <https://infdahai.github.io/my-blog/>
- Plan 原档：`/Users/disaster/.claude/plans/plan-system-prompt-gleaming-pinwheel.md`（仅本机可见）
