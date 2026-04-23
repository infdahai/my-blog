








---
citekey: "{{citekey}}"
title: "{{title}}"
authors: [{% for c in creators %}"{{c.firstName}} {{c.lastName}}"{% if not loop.last %}, {% endif %}{% endfor %}]
year: {{date | format("YYYY")}}
venue: "{{publicationTitle}}"
url: "{{URL}}"
doi: "{{DOI}}"
zotero_select: "zotero://select/library/items/{{itemKey}}"
tags: [paper, embodied-ai{% for t in tags %}, "{{t.tag}}"{% endfor %}]
status: unread   # unread | reading | done
rating:          # 1-5
created: {{importDate | format("YYYY-MM-DD")}}
---

# {{title}}

> {% for c in creators %}{{c.firstName}} {{c.lastName}}{% if not loop.last %}, {% endif %}{% endfor %} · {{date | format("YYYY")}}{% if publicationTitle %} · *{{publicationTitle}}*{% endif %}
> [Open in Zotero](zotero://select/library/items/{{itemKey}}){% if URL %} · [Source]({{URL}}){% endif %}

## TL;DR
<!-- 一句话总结 -->

## Problem
<!-- 论文要解决什么问题？为什么重要？ -->

## Method
<!-- 核心方法、关键设计、与已有工作的差异 -->

## Results
<!-- 主要实验、关键指标、消融发现 -->

## My Notes
<!-- 个人批注：值得借鉴的点、存疑、与具身智能场景的关联 -->

## Highlights & Annotations
{% persist "annotations" %}
{% set annotations = annotations | filterby("date", "dateafter", lastImportDate) %}
{% if annotations.length > 0 %}
### Imported on {{importDate | format("YYYY-MM-DD HH:mm")}}
{% for a in annotations %}
{%- if a.annotatedText %}
> {{a.annotatedText}}{% if a.pageLabel %} (p. {{a.pageLabel}}){% endif %}
{% endif -%}
{%- if a.imageRelativePath %}
![[{{a.imageRelativePath}}]]
{% endif -%}
{%- if a.comment %}
**Note:** {{a.comment}}
{% endif %}
{% endfor %}
{% endif %}
{% endpersist %}

## Zotero Notes
{% for note in notes %}
{{note.note}}
{% endfor %}

## Related
<!-- [[other-paper-citekey]] -->
