# Portfolio · 2027 届校招（AI 应用 / 后端方向）

主投方向为 AI 应用开发：**Agent 构建 → RAG 检索 → 效果评测**的完整闭环。全部项目 mock 模式离线可复现、GitHub Actions CI 全绿、README 明示"已实测 / 静态交付"边界，不写未测数据。

## 置顶项目

| 仓库 | 一句话 | 技术栈 |
|---|---|---|
| [campus-study-agent](https://github.com/HUG-thefuture/campus-study-agent) | 自研 ReAct Agent：8 工具声明式注册、写操作确认门、多步组合意图、SQLite 轨迹回放；内置 /demo 聊天演示台 | FastAPI · SQLite · pytest×86 |
| [course-kb-qa](https://github.com/HUG-thefuture/course-kb-qa) | 课程知识库 RAG：切分→TF-IDF 检索→引用溯源→无依据拒答；40 条评测（命中/引用 100%、拒答 95%） | FastAPI · TF-IDF · numpy |
| [agent-eval](https://github.com/HUG-thefuture/agent-eval) | Agent 评测平台：50 条黄金集五维判定、baseline 45/50、能力降级 A/B（编造 0 条） | Python 标准库 |
| [ai-workflow-toolkit](https://github.com/HUG-thefuture/ai-workflow-toolkit) | 显式编排工作流：校验/重试/转人工 + 邮件意图签名判重（含 Dify DSL 对照） | Python 标准库 |
| [campus-marketplace-java](https://github.com/HUG-thefuture/campus-marketplace-java) | 校园二手交易后端：订单状态机、JWT 越权防护、短链服务 | Spring Boot 3 · MyBatis · MySQL |
| [campus-lab-reserve](https://github.com/HUG-thefuture/campus-lab-reserve) | 设备预约 + 打卡双服务：时段冲突校验、角色控制；56 例 HTTP 回归；一键演示种子 | FastAPI · SQLAlchemy 2.0 |
| [course-api-testing](https://github.com/HUG-thefuture/course-api-testing) | 接口自动化全家桶：39 例参数化回归 + Selenium 冒烟 + 测试计划/用例/缺陷单工件 | pytest · requests · Selenium |
| [campus-events-vue](https://github.com/HUG-thefuture/campus-events-vue) | 校园活动运营前端：日历/报名/审批/看板，mock 离线可演示；含可复用后台组件库 | Vue 3 · Element Plus · Pinia |

## 工程习惯

- 数据单一事实源 + 契约校验 + 渲染级门禁；公开前隐私扫描（无密钥、无个人信息）
- 评测先行：离线评测集随仓库交付，改动即回归
- 诚实边界：每个 README 都有「已知边界」节，静态交付如实标注

> 求职沟通请通过简历投递渠道联系。
