<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&amp;color=0:38BDF8,55:7DD3FC,100:BAE6FD&amp;height=150&amp;section=header&amp;text=Han%20Shenghao&amp;fontColor=082F49&amp;fontSize=42&amp;fontAlignY=38&amp;desc=Backend%20Engineering%20%C3%97%20Agent%20Systems&amp;descSize=16&amp;descAlignY=68" alt="Han Shenghao — Backend Engineering × Agent Systems" />

<p align="center">
  <img width="520" src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&amp;weight=600&amp;size=19&amp;pause=1800&amp;color=14B8A6&amp;center=true&amp;vCenter=true&amp;width=520&amp;height=38&amp;lines=Backend+%26+Agent+Engineering;Java+%2F+Spring+Cloud+%2F+LangGraph" alt="Backend and Agent Engineering · Java · Spring Cloud · LangGraph" />
</p>

<p align="center">
  <a href="https://github.com/Tim051216?tab=repositories"><img src="https://img.shields.io/badge/Projects-0F172A?style=flat-square&logo=github&logoColor=white" alt="Projects" /></a>
  <a href="https://github.com/Tim051216?tab=activity"><img src="https://img.shields.io/badge/Open_Source-0F766E?style=flat-square&logo=opensourceinitiative&logoColor=white" alt="Open source activity" /></a>
  <img src="https://img.shields.io/badge/Nanjing%2C_China-334155?style=flat-square&logo=googlemaps&logoColor=white" alt="Nanjing, China" />
  <img src="https://img.shields.io/badge/Open_to_Internships-F59E0B?style=flat-square" alt="Open to internships" />
  <img src="https://komarev.com/ghpvc/?username=Tim051216&amp;label=Profile%20views&amp;color=0F766E&amp;style=flat-square" alt="Profile views" />
</p>

<p align="center">
  <img width="40" height="40" src="https://raw.githubusercontent.com/tandpfun/skill-icons/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/Java-Dark.svg" alt="Java" title="Java" />
  <img width="40" height="40" src="https://raw.githubusercontent.com/tandpfun/skill-icons/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/Spring-Dark.svg" alt="Spring" title="Spring" />
  <img width="40" height="40" src="https://raw.githubusercontent.com/tandpfun/skill-icons/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/Python-Dark.svg" alt="Python" title="Python" />
  <img width="40" height="40" src="https://raw.githubusercontent.com/tandpfun/skill-icons/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/FastAPI.svg" alt="FastAPI" title="FastAPI" />
  <img width="40" height="40" src="https://raw.githubusercontent.com/tandpfun/skill-icons/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/TypeScript.svg" alt="TypeScript" title="TypeScript" />
  <img width="40" height="40" src="https://raw.githubusercontent.com/tandpfun/skill-icons/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/VueJS-Dark.svg" alt="Vue" title="Vue" />
  <img width="40" height="40" src="https://raw.githubusercontent.com/tandpfun/skill-icons/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/React-Dark.svg" alt="React" title="React" />
</p>

<p align="center">
  <img width="40" height="40" src="https://raw.githubusercontent.com/tandpfun/skill-icons/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/MySQL-Dark.svg" alt="MySQL" title="MySQL" />
  <img width="40" height="40" src="https://raw.githubusercontent.com/tandpfun/skill-icons/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/PostgreSQL-Dark.svg" alt="PostgreSQL" title="PostgreSQL" />
  <img width="40" height="40" src="https://raw.githubusercontent.com/tandpfun/skill-icons/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/Redis-Dark.svg" alt="Redis" title="Redis" />
  <img width="40" height="40" src="https://raw.githubusercontent.com/tandpfun/skill-icons/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/RabbitMQ-Dark.svg" alt="RabbitMQ" title="RabbitMQ" />
  <img width="40" height="40" src="https://raw.githubusercontent.com/tandpfun/skill-icons/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/Docker.svg" alt="Docker" title="Docker" />
  <img width="40" height="40" src="https://raw.githubusercontent.com/tandpfun/skill-icons/7f7e691e71aec64e8354bf697835e009d1ad80f8/icons/Linux-Dark.svg" alt="Linux" title="Linux" />
</p>

## 💼 实习经历

### 苏宁易购｜苏宁云财 · 后端开发实习生

**2026.08–2026.10** · 参与智能财务平台后端开发，覆盖票据 OCR、凭证审批和月末结账。

- **异步票据处理** · 基于 RocketMQ 和 MinIO 串联上传、识别、入库和制证，使用幂等消费、重试和死信队列保障最终一致性。1,000 张票据压测中，接口 P95 从 **1.86 s 降至 72 ms**，吞吐量达 **18.5 张/s**，处理成功率为 **99.8%**。
- **凭证清理与月结并发** · 使用 CompletableFuture 并行清理，配合 Redisson 分布式锁控制月结并发。清理 5,000 张凭证及 35,000 条关联数据的平均耗时从 **3,348 ms 降至 2,708 ms**。
- **OCR 安全与可观测性** · 实现请求签名、重放防护、传输加密和 OpenTelemetry 审计追踪，安全审计链路的 P95 增量为 **1.94 ms**。
- **认证与审批** · 参与 Sa-Token、JWT 和 Redis 统一认证及多公司 RBAC 建设，并用 Flowable BPMN 将凭证审批重构为可配置流程。

### 中科安芯（江苏）有限公司 · 后端开发实习生

**2026.02–2026.04** · 参与企业级 SaaS 微服务平台开发，涉及网关、数据中心、IoT、CRM 和 ERP 等模块。

- **元数据采集** · 使用 XXL-Job 调度异构数据源的采集任务，通过专用线程池和有界队列并行处理 JDBC I/O。96 个任务的平均耗时从 **477 ms 降至 299 ms（37.2%）**。
- **登录与权限** · 参与 BCrypt、OAuth2 双令牌、Redis 登录态以及网关统一鉴权建设，并配合 Vue 3 管理端联调动态路由、权限加载和菜单渲染。

## 👋 关于我

我是 **韩盛豪**，南京林业大学人工智能专业本科生，专注于 **后端工程** 与 **Agent 系统**。

预计 **2028 年 9 月**毕业，目前正在寻找后端开发或 Agent 开发实习。

## 🚀 个人项目

### [BiliLearn](https://github.com/Tim051216/BiliLearn) — Multi-Agent Learning Platform

面向高校在线学习场景的个性化学习平台，由学习画像、知识检索与答疑、学习规划、资源生成、测评反馈五类智能体协同驱动。

![LangGraph](https://img.shields.io/badge/LangGraph-0F766E?style=flat-square&logo=langgraph&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-334155?style=flat-square) ![RAG](https://img.shields.io/badge/RAG-334155?style=flat-square) ![Redis](https://img.shields.io/badge/Redis-A91E32?style=flat-square&logo=redis&logoColor=white) ![RocketMQ](https://img.shields.io/badge/RocketMQ-9A3412?style=flat-square) ![RAGAS](https://img.shields.io/badge/RAGAS-6D28D9?style=flat-square)

- 使用 BM25 与 Dense 双路召回，经 RRF 融合和 Reranker 精排。相较于单路稠密检索基线，Top-1 命中率提升 **28.5%**，信息密度提升 **20.5%**，端到端准确率达 **85%+**。
- 用分层意图树识别问答、工具调用和系统指令，对低置信度请求发起澄清，意图 Top-1 准确率为 **90%**。在 ReAct 多轮执行中限制步数，并对可重试错误使用指数退避。
- 用 RAGAS 对单跳、多跳、拒答及时效样本分层评测，结合多版本 A/B 对比定位检索与生成问题，忠实度提升 **10.3%**，答案相关性提升 **8.0%**。

### [七云菜馆](https://github.com/Tim051216/qiyun-restaurant) — Distributed Restaurant System

覆盖微服务后端、管理后台与微信小程序的全栈餐饮系统，重点实践高并发场景下的缓存、流量治理和最终一致性。

![Spring Cloud](https://img.shields.io/badge/Spring_Cloud-3F6212?style=flat-square&logo=spring&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-A91E32?style=flat-square&logo=redis&logoColor=white) ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-9A3412?style=flat-square&logo=rabbitmq&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-155E75?style=flat-square&logo=mysql&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-1D4ED8?style=flat-square&logo=docker&logoColor=white)

- 使用 Redis + Lua 实现分布式令牌桶，并以 Caffeine + Redis、布隆过滤器和分布式互斥锁治理缓存问题。
- 通过原子预扣减与 RabbitMQ 异步下单，将接口平均耗时从 **497.36 ms 降至 155.66 ms（68.7%）**，配合 ACK、幂等、重试与对账保障一致性。

<p align="right"><a href="https://github.com/Tim051216?tab=repositories">Explore all projects →</a></p>

## 🌱 Open source, lately

最近在 Agent 工程生态中参与 issue 讨论、代码审阅与贡献，重点关注 typed outputs、工具调用、执行可靠性和开发者体验。

<p>
  <a href="https://github.com/google/adk-python"><img src="https://img.shields.io/badge/google%2Fadk--python-4285F4?style=flat-square&logo=google&logoColor=white" alt="google/adk-python" /></a>
  <a href="https://github.com/pydantic/pydantic-ai"><img src="https://img.shields.io/badge/pydantic%2Fpydantic--ai-E92063?style=flat-square&logo=pydantic&logoColor=white" alt="pydantic/pydantic-ai" /></a>
  <a href="https://github.com/microsoft/autogen"><img src="https://img.shields.io/badge/microsoft%2Fautogen-5E5E5E?style=flat-square&logo=microsoft&logoColor=white" alt="microsoft/autogen" /></a>
  <a href="https://github.com/strands-agents/harness-sdk"><img src="https://img.shields.io/badge/strands--agents%2Fharness--sdk-7C3AED?style=flat-square" alt="strands-agents/harness-sdk" /></a>
</p>

<p><a href="https://github.com/Tim051216?tab=activity">View public activity →</a></p>

## 🧰 Toolbox

**Backend** · Java · Spring Boot · Spring Cloud · MyBatis-Plus · Sa-Token · Flowable<br />
**Data & Middleware** · MySQL · PostgreSQL · Redis · RocketMQ · RabbitMQ · Redisson · MinIO<br />
**AI Engineering** · Agent Runtime · Harness · LangChain · LangGraph · MCP · RAG · ReAct · RAGAS<br />
**Delivery & Observability** · Linux · Docker · OpenTelemetry · Sentinel · XXL-Job

## 📈 GitHub snapshot

<p align="center">
  <img height="155" src="https://github-readme-stats.vercel.app/api?username=Tim051216&show_icons=true&hide_border=true&hide_title=true&include_all_commits=true&title_color=0F766E&text_color=64748B&icon_color=14B8A6&bg_color=00000000" alt="Han Shenghao's GitHub stats" />
  <img height="155" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Tim051216&layout=compact&hide_border=true&langs_count=6&title_color=0F766E&text_color=64748B&bg_color=00000000" alt="Most used languages" />
</p>

<p align="center">
  <img width="470" src="https://streak-stats.demolab.com?user=Tim051216&amp;theme=tokyonight&amp;hide_border=true&amp;ring=14B8A6&amp;fire=5EEAD4&amp;currStreakLabel=5EEAD4" alt="GitHub contribution streak" />
</p>

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=Tim051216&amp;theme=github-compact&amp;bg_color=0F172A&amp;color=CBD5E1&amp;line=14B8A6&amp;point=5EEAD4&amp;hide_border=true&amp;area=true" alt="Recent GitHub contribution activity" />
</p>

---

<p align="center">
  <sub>Build deliberately · measure honestly · improve continuously.</sub>
</p>
