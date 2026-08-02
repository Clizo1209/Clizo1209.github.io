---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am an undergraduate student pursuing a B.Eng. in Artificial Intelligence at [Shandong University](https://www.sdu.edu.cn/). My interests lie in LLM agents, AI service infrastructure, and production full-stack systems. I enjoy building practical software across the complete lifecycle, from requirements analysis and system design to deployment and long-term operation.

- **Date of Birth:** Dec. 2005
- **Email:** [chenlz1209@qq.com](mailto:chenlz1209@qq.com) · [chenlz1209@icloud.com](mailto:chenlz1209@icloud.com)

<span class='anchor' id='-education'></span>

# 🎓 Education

- **Shandong University**, School of Artificial Intelligence<br>
  B.Eng. in Artificial Intelligence, Sep. 2024 – Present

<span class='anchor' id='-projects'></span>

# 📦 Selected Projects

## Internal Workflow and Management Platform

*Independent Full-Stack Developer & System Administrator · Jul. 2025 – Present*

- Independently designed, developed, deployed, and maintained a suite of 10+ internal web systems used by approximately 200 active faculty members and students.
- Managed the complete software lifecycle, including requirements analysis, architecture design, full-stack development, database administration, Docker-based deployment, server operations, and ongoing maintenance.
- Digitalized workflows including comprehensive evaluation, volunteer applications, leave requests, meeting-room reservations, assignment submission, activity records, competition management, information publishing, and team recruitment.
- Processed **8,993 production submissions and applications** and recorded **44,626 page views** during the first year of operation.
- Implemented a unified authentication gateway based on the university's centralized identity service, enabling single sign-on across the internal applications.
- Built primarily with **Vue.js and Node.js**, with selected services using Python, C#, Redis, SQLite, MySQL, and PostgreSQL.

## AI Agent Service Framework

*Independent Developer · May 2025 – Aug. 2026*

- Designed and implemented a full-stack AI agent framework in Node.js and Vue, evolving from an earlier Python-based MCP campus assistant.
- Built a progressively disclosed Tools and Skills architecture with semantic capability discovery, dynamic JavaScript tools, worker-isolated execution, scoped secrets, version control, test gates, quotas, and audit logging.
- Implemented long-term memory with automatic extraction, conflict-aware updates, semantic deduplication, and retrieval weighted by relevance, recency, and importance.
- Added persistent task planning, reconnectable background execution, parallel tool calling, and automatic context compression for multi-step workflows.
- Developed a three-level knowledge system with hybrid retrieval using pgvector, Chinese full-text search, and reciprocal rank fusion.
- Integrated OpenAI-compatible, Anthropic, and Gemini model providers together with SearXNG, Crawl4AI, Redis, PostgreSQL, and Docker Compose.

## LLM Agent for User Behavior Modeling

*Team Leader · AgentSociety Challenge @ WWW 2025 · Jan. 2025 – Feb. 2025*

- Led a three-student team under the guidance of two faculty advisors and ranked **10th among 295 registered teams** in the User Modeling Track ([official results](https://tsinghua-fib-lab.github.io/AgentSocietyChallenge/pages/winners.html)).
- Developed an LLM-based agent to estimate user preferences and generate personalized reviews from historical behavior records.
- Extended the official Python baseline with prompt-engineering strategies, tool-assisted information retrieval, and structured agent workflows.

<span class='anchor' id='-leadership'></span>

# 🤝 Leadership

## Founder & President, SDU AI UniX

*Shandong University · Jun. 2025 – Aug. 2026*

- Founded and grew a student AI community to approximately **900 members** within its first year.
- Recruited and led a **50-member organizing team** responsible for technical programs, competitions, development activities, and community operations.
- Led the organization of **40+ events**, generating approximately **10,000 cumulative attendances** across courses, competitions, development programs, and community activities.

<span class='anchor' id='-honors'></span>

# 🏆 Honors & Awards

- **Outstanding Communist Youth League Member**, Shandong University, 2024–2025
- **First-Class Special Talent Scholarship (Academic Specialty Category)**, Shandong University, 2024
- **10th Place / Finalist**, User Modeling Track, AgentSociety Challenge @ WWW 2025
- **Second Prize**, AI Geeks Challenge, Shandong University, 2025
- **First Prize**, School of Artificial Intelligence Preliminary Round, China International College Students' Innovation Competition, 2025

<span class='anchor' id='-skills'></span>

# 🛠️ Technical Skills

- **LLM Agent Systems:** Agentic workflows, tool and function calling, MCP, RAG, long-term memory and context management, task planning, modular Agent Skills, multi-provider LLM integration
- **Programming:** C#, JavaScript (Node.js), Java, SQL, Python
- **Backend & Data:** Express, PostgreSQL/pgvector, MySQL, SQLite, Redis, REST API and database design, CAS-based centralized authentication and SSO
- **Infrastructure & Operations:** Docker Compose, Nginx, Linux server administration, monitoring and logging, backup and recovery, network and application security
- **AI-Assisted Software Engineering:** Extensive hands-on experience since 2024 with ChatGPT, Cursor, Windsurf, Claude Code, and Codex across requirements analysis, implementation, debugging, code review, refactoring, documentation, and maintenance

<span class='anchor' id='-hobbies'></span>

# 🔎 Interests

Photography, drone videography, and video editing.
