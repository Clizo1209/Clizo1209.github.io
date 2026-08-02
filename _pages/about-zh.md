---
permalink: /zh/
title: ""
excerpt: ""
author_profile: true
lang: zh-CN
profile_description: "人工智能本科生 · 大模型智能体与全栈系统"
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

我是山东大学人工智能专业工学学士在读本科生，主要关注大语言模型智能体、AI 服务基础设施以及生产级全栈系统。我喜欢构建解决实际问题的软件，并独立负责从需求分析、系统设计到部署运维和长期迭代的完整生命周期。

<span class='anchor' id='-education'></span>

# 🎓 教育经历

- **山东大学**，人工智能学院<br>
  人工智能专业，工学学士，2024 年 9 月—2028 年 6 月（预计）

<span class='anchor' id='-projects'></span>

# 📦 精选项目

## 学院内部工作流与管理平台

*独立全栈开发与系统运维 · 2025 年 7 月—至今*

- 独立设计、开发、部署并维护 10 余个学院内部 Web 系统，服务约 **200 名活跃师生用户**。
- 负责完整软件生命周期，包括需求分析、架构设计、全栈开发、数据库管理、基于 Docker 的部署、服务器运维与持续维护。
- 将综合评价填报、志愿申报、请销假、会议室预约、作业提交、活动记录、比赛管理、信息发布和团队招募等工作流数字化。
- 上线首年累计处理 **8,993 条正式填报与申请记录**，页面访问量达到 **44,626 PV**。
- 基于学校统一身份认证服务实现统一认证网关，为全部内部应用提供单点登录。
- 主要使用 **Vue.js 和 Node.js**，部分服务使用 Python、C#、Redis、SQLite、MySQL 与 PostgreSQL。

## AI Agent 智能服务框架

*独立开发 · 2025 年 5 月—2026 年 8 月*

- 使用 Node.js 和 Vue 设计并实现全栈 AI Agent 框架，由早期基于 Python 的校园 MCP 助手持续演进而来。
- 构建渐进式披露的 Tools 与 Skills 架构，支持语义能力发现、动态 JavaScript 工具、Worker 隔离执行、密钥权限控制、版本管理、测试门禁、配额限制与审计日志。
- 实现长期记忆系统，支持自动提取、冲突感知更新、语义去重，并结合相关性、时效性和重要性进行检索排序。
- 支持持久化任务规划、可重连的后台执行、并行工具调用及面向多步工作流的自动上下文压缩。
- 构建三级知识库体系，结合 pgvector、中文全文检索与倒数排名融合进行混合检索。
- 集成 OpenAI 兼容接口、Anthropic 与 Gemini 模型服务，以及 SearXNG、Crawl4AI、Redis、PostgreSQL 和 Docker Compose。

## 面向用户行为建模的 LLM Agent

*队长 · WWW 2025 AgentSociety Challenge · 2025 年 1 月—2 月*

- 带领 3 人学生团队，在 2 位指导教师的指导下，于用户建模赛道 **295 支报名队伍中排名第 10**。
- 开发基于大语言模型的智能体，根据历史行为记录估计用户偏好并生成个性化评论。
- 在官方 Python baseline 基础上加入提示词工程、工具辅助信息检索与结构化 Agent 工作流。

<span class='anchor' id='-leadership'></span>

# 🤝 组织领导经历

## 山东大学学生 AI UniX 创新协会创始人、社长

*山东大学 · 2025 年 6 月—2026 年 8 月*

- 创立学生 AI 社群，并在首年发展至约 **900 名成员**。
- 招募并带领一支 **50 人核心团队**，负责技术课程、竞赛、研发活动及社群运营。
- 组织开展 **40 余场活动**，涵盖课程、竞赛、研发项目及互动活动，累计参与约 **10,000 人次**。

<span class='anchor' id='-honors'></span>

# 🏆 荣誉与奖项

- **山东大学优秀共青团员**，2024 年、2025 年
- **山东大学特长奖学金（学科特色类）一等奖**，2024—2025 学年
- **用户建模赛道第 10 名 / 决赛选手**，WWW 2025 AgentSociety Challenge
- **AI 极客挑战赛二等奖**，山东大学，2025 年
- **中国国际大学生创新大赛人工智能学院院级选拔赛一等奖**，2025 年

<span class='anchor' id='-skills'></span>

# 🛠️ 技术能力

- **大模型智能体系统：** Agent 工作流、工具与函数调用、MCP、RAG、长期记忆与上下文管理、任务规划、模块化 Agent Skills、多模型服务商接入
- **编程语言：** C#、JavaScript（Node.js）、Java、SQL、Python
- **后端与数据：** Express、PostgreSQL/pgvector、MySQL、SQLite、Redis、REST API 与数据库设计、基于 CAS 的统一认证与单点登录
- **基础设施与运维：** Docker Compose、Nginx、Linux 服务器管理、监控与日志、备份与恢复、网络与应用安全
- **AI 辅助软件工程：** 自 2024 年起深度使用 ChatGPT、Cursor、Windsurf、Claude Code 与 Codex，覆盖需求分析、功能实现、调试、代码审查、重构、文档编写与长期维护

<span class='anchor' id='-hobbies'></span>

# 🔎 兴趣爱好

摄影、无人机航拍与视频剪辑。
