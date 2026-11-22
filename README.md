<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,45:1D4ED8,100:06B6D4&height=230&section=header&text=Han%20Shenghao&fontColor=ffffff&fontSize=54&fontAlignY=35&desc=Backend%20Engineering%20%C2%B7%20AI%20Agents%20%C2%B7%20Distributed%20Systems&descSize=17&descAlignY=57&animation=fadeIn" alt="Han Shenghao banner"/>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&pause=1600&color=1D4ED8&center=true&vCenter=true&width=680&lines=Backend+%26+Agent+Developer+Intern;Java+%7C+Spring+Cloud+%7C+LangGraph;Finance+Backend+%7C+AI+Agent+Systems" alt="Typing introduction"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/南京林业大学-人工智能-1D4ED8?style=for-the-badge" alt="Nanjing Forestry University"/>
  <img src="https://img.shields.io/badge/Focus-Backend%20%26%20Agent%20Engineering-0F766E?style=for-the-badge" alt="focus"/>
  <img src="https://img.shields.io/badge/Status-Open%20to%20Internships-F59E0B?style=for-the-badge" alt="status"/>
  <img src="https://komarev.com/ghpvc/?username=Tim051216&label=Profile%20views&color=1D4ED8&style=for-the-badge" alt="Profile views"/>
</p>

## 👋 About me

你好，我是 **韩盛豪（Tim051216）**，南京林业大学人工智能专业本科生，拥有智能财务平台和企业级 SaaS 平台后端实习经历，正在寻找后端开发与 Agent 开发实习机会。

我的工程兴趣集中在两条线：一是使用 **Java / Spring Boot / Spring Cloud** 构建高并发、可观测的后端服务；二是使用 **LangChain / LangGraph / MCP** 把大模型能力落地为可控、可评测的多 Agent 系统。

我关注的不只是“能跑起来”，也关注鉴权安全、流程一致性、并发治理、可观测性、检索质量和 Agent 执行边界。

## 🎓 Education

**南京林业大学（双一流） · 人工智能本科 · 2024.09 — 2028.09**

## 🧰 Engineering toolkit

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,spring,python,fastapi,ts,vue,react,mysql,redis,rabbitmq,docker,linux&perline=12" alt="Engineering toolkit"/>
</p>

**Backend** · Java · Spring Boot · Spring Cloud · MyBatis-Plus · Sa-Token · Flowable<br>
**Data & Middleware** · MySQL · PostgreSQL · Oracle · Redis · RocketMQ · RabbitMQ · Redisson · MinIO<br>
**AI Engineering** · LangChain · LangGraph · MCP · RAG · ReAct · RAGAS · Dify · Harness Engineering<br>
**Delivery & Observability** · Linux · Docker · Alibaba Cloud ECS · OpenTelemetry · Sentinel · XXL-Job

## 💼 Experience

**Backend Developer Intern · 苏宁易购｜苏宁云财 · 2026.07 — 2026.09**

- 参与业财一体化智能财务平台后端开发，覆盖票据 OCR、规则制证、凭证审批、月末结账、财务报表与电子档案等核心链路。
- 基于 Sa-Token + JWT + Redis 建设统一认证与多公司 RBAC 权限模型，以 `appCode` 区分业务系统、`companyId` 隔离租户。
- 为 OCR 链路设计 IP 白名单、HMAC-SHA256、Timestamp/Nonce 与 AES-GCM 安全机制，并通过 OpenTelemetry 建立审计与追踪链路；1000 次请求压测下 P95 额外开销仅 **5.1 ms**。
- 使用 RocketMQ + MinIO 解耦文件、OCR 与财务服务，构建“上传—识别—入库—制证”异步流水线；1000 张票据压测下接口 P95 从 **1.86 s 降至 72 ms**，成功率 **99.8%**、重复制证率 **0%**。
- 使用 Flowable BPMN 将硬编码审批状态迁移为可配置流程，覆盖提交、审核、反审核、驳回和重提五类动作。
- 通过 CompletableFuture、Redisson 分布式锁和有界线程池治理批处理与文件并发；5000 张凭证级联清理从 **4.9 s 降至 2.9 s（40.8%）**，100 个并发月结请求仅一个进入临界区。

**Backend Developer Intern · 中科安芯（江苏）有限公司 · 2026.02 — 2026.04**

- 在企业级 SaaS 微服务平台中参与网关、系统管理、数据中心、IoT、CRM 与 ERP 模块开发。
- 针对元数据采集等 IO 密集任务设计专属 `ThreadPoolTaskExecutor` 线程池；96 个 JDBC 任务压测下平均耗时从 **477 ms 降至 299 ms（37.2%）**。
- 参与 Vue3 + TypeScript + Vite + Element Plus 管理端联调，打通动态路由、权限加载与菜单渲染链路。
- 设计分层登录安全方案：BCrypt 密码校验、OAuth2 access/refresh 双令牌、Redis 登录态、网关统一鉴权、Spring Security + RBAC 权限控制及 AES 传输加密。

## 🚀 Featured work

### [BiliLearn](https://github.com/Tim051216/BiliLearn) · Multi-Agent Learning Platform

面向高校在线学习场景，由学习画像、知识检索与答疑、学习规划、资源生成、测评反馈五类智能体协同驱动的个性化学习平台。

<p>
  <img src="https://img.shields.io/badge/LangChain%20%2B%20LangGraph-Agent%20Orchestration-1D4ED8?style=flat-square" alt="LangGraph"/>
  <img src="https://img.shields.io/badge/MCP-Tool%20Integration-0F766E?style=flat-square" alt="MCP"/>
  <img src="https://img.shields.io/badge/RAGAS-Automated%20Evaluation-7C3AED?style=flat-square" alt="RAGAS"/>
</p>

- 基于 Redisson 分布式限流器和 Redis + Lua 令牌桶按用户、模型维度管控配额，以信号量约束推理并发；RocketMQ 削峰排队，结合 vLLM、Sentinel、多模型路由与全链路追踪提升高并发可用性。
- 以 MD5 精确缓存 + RedisStack HNSW 语义缓存复用检索结果，降低重复向量计算开销。
- 采用数据库任务表轮询与事务原子抢占实现多实例分布式消费，完成文档解析、切片和向量入库，避免重复解析与向量化。
- 设计意图定向 + 全局向量双路召回和检索后置治理，Top-1 召回命中率提升 **28.5%**、上下文精准度提升 **20.5%**，知识检索综合准确率达到 **85%+**。
- 构建分层意图识别、ReAct 多轮 Agent、UID 会话隔离、对话摘要和三层执行安全边界，意图 Top-1 准确率 **90%+**。
- 建立覆盖检索性能、响应延迟和生成质量 20 余项指标的 RAGAS 评测体系，忠实度提升 **10.3%**，答案相关性提升 **8.0%**。

### [七云菜馆](https://github.com/Tim051216/qiyun-restaurant) · AI-enabled Restaurant System

全栈餐饮管理系统，包含微服务后端、管理后台和微信小程序。

- Redis + Lua 分布式令牌桶完成流量整形与秒杀令牌校验。
- Caffeine + Redis 二级缓存、布隆过滤器与分布式互斥锁，系统化应对穿透、击穿和热点 Key。
- Redis 原子预扣减 + RabbitMQ 异步下单，将接口平均耗时从 **497.36 ms 降至 155.66 ms（68.7%）**，并通过回滚、对账、ACK、幂等和重试保障最终一致性。

## 📌 More projects

| Project | Focus |
| --- | --- |
| [BiliLearn](https://github.com/Tim051216/BiliLearn) | Multi-Agent 个性化学习平台 |
| [Liftoff](https://github.com/Tim051216/liftoff) | AI-powered mock interview simulator |
| [Liftoff-interview](https://github.com/Tim051216/Liftoff-interview) | Java 在线编程与面试准备平台 |
| [A3-portal-web](https://github.com/Tim051216/A3-portal-web) | TypeScript Web 门户应用 |
| [PersonalityCourt](https://github.com/Tim051216/PersonalityCourt) | TypeScript 应用项目 |

## 📈 GitHub activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Tim051216&show_icons=true&hide_border=true&theme=tokyonight&rank_icon=github" alt="GitHub stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Tim051216&layout=compact&hide_border=true&theme=tokyonight" alt="Top languages"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Tim051216&theme=tokyonight&hide_border=true" alt="GitHub streak"/>
</p>

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=Tim051216&theme=tokyo-night&hide_border=true&area=true" alt="Contribution activity graph"/>

## 🌱 Now learning

- Production-grade Agent evaluation and observability
- Reliable distributed systems and performance engineering
- Better technical documentation, testing, and open-source collaboration

<p align="center">
  <a href="https://github.com/Tim051216"><img src="https://img.shields.io/badge/GitHub-@Tim051216-181717?style=for-the-badge&logo=github" alt="GitHub"/></a>
</p>

<p align="center"><sub>Build deliberately · measure honestly · improve continuously</sub></p>
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:06B6D4,55:1D4ED8,100:0F172A&height=100&section=footer" alt="footer"/>
