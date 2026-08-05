Open Source Contributor @omegaUp & @pipe-cd, Backend Developer @BITAcademia, B.Tech AI & ML @BIT Mesra.

[![Linkedin Badge](https://img.shields.io/badge/-yash--agarwal-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/yash-agarwal-1b5b17282/)](https://www.linkedin.com/in/yash-agarwal-1b5b17282/)
[![GitHub Badge](https://img.shields.io/badge/-Yashagarwal9798-181717?style=flat-square&logo=github&logoColor=white&link=https://github.com/Yashagarwal9798)](https://github.com/Yashagarwal9798)
[![Gmail Badge](https://img.shields.io/badge/-yashagarwal9798-D14836?style=flat-square&logo=Gmail&logoColor=white&link=mailto:yashagarwal9798@gmail.com)](mailto:yashagarwal9798@gmail.com)

### Works

**Open Source**

1. **[omegaUp](https://github.com/omegaup/omegaup)**: 67 PRs contributed (47 merged) to a large-scale competitive programming platform used across Latin America.
   * **Key Contributions:**
      * Shipped **5+ features** — Problem Notes (per-problem annotations), character limit indicators, and a password visibility toggle.
      * Fixed **race conditions** in task assignment and optimized correlated subqueries in the DAO layer.
      * Diagnosed and resolved a critical **Docker crash-loop** breaking every local environment, restoring a working dev setup for all contributors.
      * Implemented a **multi-language spell-checking CI workflow** backed by a 300+ term custom dictionary.
      * Improved the **`/assign` and `/unassign` contributor bot workflows**, surfacing remaining self-assign counts and fixing misleading unassign messages.
      * Authored the tracking proposal and roadmap for a full **Bootstrap 4 → Bootstrap 5 migration** of the frontend.
      * Added missing unit tests and resolved **15+ UI bugs**.
   * **Stack:** PHP, Vue.js, TypeScript, Docker

2. **[PipeCD](https://github.com/pipe-cd/pipecd)**: CNCF continuous delivery platform — 9 PRs contributed (8 merged).
   * **Key Contributions:**
      * Hardened CI by adding **read-only `GITHUB_TOKEN` permissions** to validation workflows.
      * Added **concurrency groups** to build workflows, cancelling superseded runs and cutting redundant CI compute.
      * Fixed the **first-time-contributor welcome check** so new contributors are greeted correctly.
      * Repaired broken links and stale Hugo front matter across `CONTRIBUTING.md` and the CI docs.
      * Introduced a **`CLAUDE.md`** importing the existing Copilot instructions, unifying AI-assistant guidance for the repo.
   * **Stack:** Go, GitHub Actions, Docker, Kubernetes

---

**Internships / Professional Experience**

1. **[BITAcademia](#)**: Backend Developer on an academic management platform for BIT Mesra.
   * **Key Contributions:**
      * Engineered **transaction-safe RESTful APIs** for academic mentor reassignment.
      * Implemented strict **Role-Based Access Control (RBAC)** via custom middleware for master admins.
      * Built authentication with **JWT + bcrypt** and patched existing security vulnerabilities.
      * Integrated **Cloudinary, Multer, and excel.js** for media handling and data export.
   * **Stack:** Node.js, Express.js, MongoDB, JWT

---

**Projects**

1. **[AgentStack Radar](https://github.com/Yashagarwal9798/Agentstack)**
   A living catalog for AI coding agents, with a memory of what worked for *you*. Built solo during the Localhost:6767 Supermemory Local Hackathon.
   * **Global discovery pipeline** (daily GitHub Actions cron) monitors the MCP Registry, `anthropics/skills`, and Hacker News; an LLM classifies, verifies, and extracts structured **Capability Cards** into immutable, sha256-checksummed catalog releases.
   * **Local-first CLI** pulls those releases into **Supermemory Local**, so ranking runs with zero LLM catalog calls and nothing private ever leaves the machine.
   * **Two-path memory model** — deterministic verdicts adjust scores directly, while semantic experience narratives transfer *pattern-level* lessons across unrelated projects.
   * **Approval-gated applier** writes only text files (`.claude/skills/`, `.mcp.json`, `CLAUDE.md`, `stack.lock.json`) and never executes commands; every recommendation and rejection is explained with trust tier, permissions, and provenance.
   * Published to npm as **`agentstack-radar`**.
   * **Stack:** TypeScript, Node.js, Supermemory Local, Zod, GitHub Actions

2. **[Automatic Deploy](https://github.com/Yashagarwal9798/automated-deploy)**
   CLI-based deployment tool for deploying Express, Django, Go, and Spring Boot apps to AWS ECS.
   * Detects frameworks automatically via file analysis.
   * Uses **Gemini AI to generate production-ready Dockerfiles** with safe fallback templates.
   * Automates end-to-end AWS infrastructure with **idempotent resource creation logic** via AWS SDK.
   * Reduced deployment from **30+ steps to 3**, cutting containerization time by **90%**.
   * Published to npm as **`automatic-deploy`**.

3. **[SupplySense](#)**
   Context-aware demand forecasting and inventory platform for small retailers.
   * Forecasting engine built on **Facebook Prophet + Gemini AI**, delivering 6-week predictions.
   * Dynamically integrates **real-world signals** like weather and disease outbreaks.
   * **Gemini Vision OCR** for digitizing handwritten ledgers.
   * **2-way WhatsApp bot** for real-time automated reorder alerts.
   * **Stack:** FastAPI, React, Prophet, Gemini AI, PostgreSQL, Docker

---

**Achievements**

* **Amazon ML Summer School '25 Scholar** — selected from 1,00,000+ applicants (Top 0.3%).
* **National Semi-Finalist, Flipkart GRiD 7.0 (2025)** — recognized for innovation at a national-level competition.
* **Finalist, IEEE MegaProject** — top 7 among 45+ teams.
* **7th rank, CodeZilla** by ACM BIT-Mesra at Pantheon Techfest — against 50+ teams.
* **30th rank, IEEE Recruitment Contest** — out of 300+ participants.

---

**Competitive Programming**

[Codeforces](https://codeforces.com/profile/yash_agarwal9798) &nbsp;•&nbsp; [LeetCode](https://leetcode.com/u/nepolian9798/) &nbsp;•&nbsp; [CodeChef](https://www.codechef.com/users/nepolian9798)

---

**Tech**

`C` `C++` `Python` `Java` `JavaScript` `TypeScript` `PHP` `Go`
`Node.js` `Express.js` `React.js` `Vue.js` `FastAPI`
`MongoDB` `PostgreSQL` `SQL`
`AWS` `Docker` `Kubernetes` `GitHub Actions` `Render` `Vercel` `Git` `Linux` `Postman`
`Neural Networks (ANN, CNN, RNN, LSTM)` `Transformers`
