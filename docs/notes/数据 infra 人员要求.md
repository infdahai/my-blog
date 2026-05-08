
**最匹配画像**

1. **云原生数据基础设施工程师**
    

- 熟 K8s、对象存储、Postgres/OLTP、消息队列/工作流系统、服务可观测性。
    
- 做过多租户、配额、限流、回压、容灾、灰度、部署、迁移。
    
- 能把数据管线当成“线上系统”而不是“离线任务”来设计。
    

2. **分布式存储 / 数据库 / 查询系统工程师**
    

- 理解 WAL、事务、索引、分区、Compaction、LSM/B-Tree、MVCC、一致性、复制、恢复。
    
- 不一定真的写过数据库内核，但至少能讲清楚数据库为什么这么设计。
    
- 如果做过 Doris、ClickHouse、HBase、TiDB、CockroachDB、StarRocks、Kafka、Flink 内核或存储层，会比纯数仓应用更有价值。
    

3. **AI/机器人数据平台工程师**
    

- 做过大文件、多模态数据、视频/传感器/轨迹数据、数据集版本、标注/审核、质量检查、训练数据生产。
    
- 熟 S3/MinIO、Parquet/Lance/Delta/Iceberg、元数据管理、数据血缘。
    
- 能理解“数据不是表，是资产和生命周期”。
    

**传统数仓候选人的问题**

他们常见强项是：

- SQL 开发
    
- ETL 编排
    
- 离线批处理
    
- 指标口径
    
- 报表/企业数仓模型
    
- Doris/Hive/Spark/Flink 应用层使用
    

但你这里更需要的是：

- 在线上传接入
    
- 多租户隔离
    
- 对象存储路径设计
    
- 元数据一致性
    
- workflow orchestration
    
- K8s 部署和恢复
    
- 回压、限流、队列堆积处理
    
- schema migration
    
- 大文件/多模态数据处理
    
- 数据质量、审核、可追踪交付
    

所以如果一个人只会“把业务表抽进 Doris，然后建宽表出报表”，确实不太匹配。

**你可以把岗位定义成**

> _Cloud-native Data Infrastructure Engineer for embodied AI / robotics data platform._

中文可以叫：

> _具身智能数据基础设施工程师 / 云原生数据平台工程师 / 多模态数据 Infra 工程师。_

不要写成“大数据开发工程师”，否则简历会继续涌入数仓 ETL 人群。

**筛选关键词**

简历里优先看这些：

- Kubernetes / Helm / Terraform / Argo / Prometheus / Grafana
    
- S3 / MinIO / OSS / 对象存储
    
- Postgres / MySQL / distributed database / TiDB / CockroachDB / ClickHouse / Doris kernel
    
- Temporal / Airflow / Dagster / workflow orchestration
    
- Kafka / Pulsar / queue / backpressure
    
- data lake / Iceberg / Delta / Lance / Parquet
    
- schema migration / Alembic / Flyway / Liquibase
    
- multi-tenant / quota / rate limit / isolation
    
- observability / SLO / incident / recovery
    
- robotics / autonomous driving / video data / sensor data / multimodal dataset
    

**面试时重点问**

1. “如果 1000 台设备同时上传大文件，系统怎么做限流、排队、失败恢复？”
    
2. “对象存储和 Postgres 元数据之间如何保证一致性？”
    
3. “生产数据库 schema 怎么迁移，不能 drop schema 怎么办？”
    
4. “K8s 里 worker 被杀、队列堆积、DB 短暂不可用，系统怎么恢复？”
    
5. “你怎么设计一个多租户数据集版本和血缘系统？”
    
6. “讲一个你处理过的数据平台线上事故。”
    
7. “解释一下数据库索引、事务、WAL、MVCC 或 compaction 中任意一个机制。”
8. 
所以候选人不一定每项都做过，但至少要能自然理解这些问题：

- 为什么 Postgres 只放元数据，大文件放对象存储？
    
- 为什么上传接口要有 backpressure？
    
- 为什么 worker 失败不能导致 episode 卡死？
    
- 为什么生产 DB 不能 drop schema？
    
- 为什么 K8s 里不能依赖 host Docker 服务？
    
- 为什么多租户/设备维度要从第一天进入表结构和路径设计？