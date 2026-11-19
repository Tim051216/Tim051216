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

## 🧰 Engineering toolkit

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,spring,python,fastapi,ts,vue,react,mysql,redis,rabbitmq,docker,linux&perline=12" alt="Engineering toolkit"/>
</p>

**Backend** · Java · Spring Boot · Spring Cloud · MyBatis-Plus · Sa-Token · Flowable<br>
**Data & Middleware** · MySQL · PostgreSQL · Oracle · Redis · RabbitMQ · Redisson · MinIO<br>
**AI Engineering** · LangChain · LangGraph · MCP · RAG · ReAct · RAGAS · Dify<br>
**Delivery & Observability** · Linux · Docker · Alibaba Cloud ECS · OpenTelemetry · XXL-Job

## 💼 Experience

**Backend Developer Intern · 苏宁易购｜苏宁云财 · 2026.07 — 2026.09**

- 参与业财一体化智能财务平台后端开发，覆盖票据 OCR、规则制证、凭证审批、月末结账、财务报表与电子档案等核心链路。
- 基于 Sa-Token + JWT + Redis 建设统一认证与多公司 RBAC 权限模型；1000 次并发鉴权压测成功率 **100%**，P95 耗时 **48 ms**。
- 为 OCR 链路设计 IP 白名单、HMAC-SHA256、Timestamp/Nonce 与 AES-GCM 安全机制，并通过 OpenTelemetry 建立审计与追踪链路；P95 额外开销 **5.1 ms**。
- 使用 Flowable BPMN 重构凭证审批流程；500 张凭证批量审批耗时 **4.2 s**、吞吐量 **119 条/s**，业务与流程状态一致率 **100%**。
- 通过 CompletableFuture、Redisson 分布式锁和有界线程池治理批处理与文件并发；5000 张凭证级联清理耗时降低 **40.8%**，100 个 1 MB 文件上传耗时降低 **64.8%**。

**Backend Developer Intern · 中科安芯（江苏）有限公司 · 2026.02 — 2026.04**

- 在企业级 SaaS 微服务平台中参与网关、系统管理、数据中心、IoT、CRM 与 ERP 模块开发。
- 针对元数据采集等 IO 密集任务设计专属 `ThreadPoolTaskExecutor` 线程池；96 个 JDBC 任务压测下平均耗时从 **477 ms 降至 299 ms（37.2%）**。
- 参与 Vue3 + TypeScript + Vite + Element Plus 管理端联调，打通动态路由、权限加载与菜单渲染链路。
- 设计分层登录安全方案：BCrypt 密码校验、OAuth2 access/refresh 双令牌，以及可选 AES 传输加密。

## 🚀 Featured work

### BiliLearn · Multi-Agent Learning Platform

面向在线智能教育场景的多 Agent 学习平台，使用 LangGraph 编排知识库问答、工具调用和学习流程。

<p>
  <img src="https://img.shields.io/badge/LangChain%20%2B%20LangGraph-Agent%20Orchestration-1D4ED8?style=flat-square" alt="LangGraph"/>
  <img src="https://img.shields.io/badge/MCP-Tool%20Integration-0F766E?style=flat-square" alt="MCP"/>
  <img src="https://img.shields.io/badge/RAGAS-Automated%20Evaluation-7C3AED?style=flat-square" alt="RAGAS"/>
</p>

- Redis 信号量 + ZSET + Pub/Sub + Lua 实现分布式公平排队限流，并通过 SSE 实时推送队列状态。
- MD5 精确缓存与 RedisStack HNSW 语义缓存复用检索结果；多模型路由、熔断降级与全链路追踪提升并发可用性。
- 采用多实例分布式架构完成文档入库、切片和向量写入，通过 MySQL 悲观行锁实现任务抢占，避免多节点重复解析与向量化。
- 设计意图定向 + 全局向量双路召回，Top-1 召回命中率提升 **28.5%**，知识检索综合准确率达到 **85%+**。
- 构建分层意图识别、ReAct 多轮 Agent、UID 会话隔离和三层执行安全边界，意图 Top-1 准确率 **90%+**。
- 建立覆盖检索、延迟、生成质量的 RAGAS 评测体系，忠实度提升 **10.3%**，答案相关性提升 **8.0%**。

### [七云菜馆](https://github.com/Tim051216/qiyun-restaurant) · AI-enabled Restaurant System

全栈餐饮管理系统，包含微服务后端、管理后台和微信小程序。

- Redis + Lua 分布式令牌桶完成流量整形与秒杀令牌校验。
- Caffeine + Redis 二级缓存、布隆过滤器与分布式互斥锁，系统化应对穿透、击穿和热点 Key。
- Redis 原子预扣减 + RabbitMQ 异步下单，将接口平均耗时从 **497.36 ms 降至 155.66 ms（68.7%）**，并通过回滚、对账、ACK、幂等和重试保障最终一致性。

## 📌 More projects

| Project | Focus |
| --- | --- |
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
