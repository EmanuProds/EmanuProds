<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=2500&pause=1000&color=6F8396&center=true&vSRVWidth=40&width=680&lines=Hi%2C+I'm+Emanuel+da+Costa+Pereira!;Software+Developer+%7C+Computer+Science+Student;I+build+systems+end-to-end;Backend+in+Go%2C+frontend+in+React+%2B+TypeScript;Designing+my+own+AI+agent+harness;Administering+cloud+infra+on+Oracle+Cloud;Turning+logic+into+solutions" alt="Typing SVG: Hi, I'm Emanuel da Costa Pereira — Software Developer, CS Student, Go backend, AI harness, Oracle Cloud" />

<p align="center">
  <em>Turning complex legacy problems into agile, scalable, and automated solutions.</em>
</p>

---

### 🧭 About me

I'm the **sole software developer at Perains ON Technology** (since May 2026), where I research, architect, design, and ship an ERP for Brazilian accounting — from database schema and tax rules to UI, documents generation, and CI. I also run my own cloud infrastructure on **Oracle Cloud**.

- Pursuing a **Bachelor's in Computer Science** at Descomplica Uniamerica (Class of 2029)
- Building and modernizing **Perains ON Systems** with Go, TypeScript, React, and PostgreSQL
- Administering **Oracle Cloud Infrastructure** environments
- Currently deepening **Cloud Computing** and **Software Architecture**
- Daily driver: Linux

---

### 🤖 AI-Assisted Engineering

I design and run my own **AI agent harness** on [OpenCode](https://opencode.ai) — the scaffolding around the model matters as much as the model itself:

- **Custom subagents & skills** — specialized agents (mapping, coding, review) with discoverable skill workflows
- **Tool integration** — LSP servers (gopls, pyright, TypeScript, Postgres) and MCP for external tools
- **Persistent memory** — SQLite-backed facts and session checkpoints that outlive the conversation
- **Model routing & evaluation** — a multi-provider router plus a 75-model evaluation battery measuring real tool-use capability

---

### 🚀 Stack & Technologies

| Category | Technologies |
| :--- | :--- |
| **Languages** | ![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) |
| **Frameworks** | ![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black) ![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white) |
| **Backend & API** | ![chi](https://img.shields.io/badge/go--chi-0A7EA4?style=for-the-badge&logo=go&logoColor=white) ![sqlc](https://img.shields.io/badge/sqlc-51384A?style=for-the-badge&logo=databases&logoColor=white) ![pgx](https://img.shields.io/badge/pgx-31648C?style=for-the-badge&logo=postgresql&logoColor=white) ![OpenAPI](https://img.shields.io/badge/OpenAPI-6BA539?style=for-the-badge&logo=openapiinitiative&logoColor=white) ![orval](https://img.shields.io/badge/orval-FF7675?style=for-the-badge&logo=json&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white) |
| **Data** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white) ![Microsoft SQL Server](https://img.shields.io/badge/Microsoft_SQL_Server-FFFFFF?style=for-the-badge&logo=microsoftsqlserver&logoColor=black) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white) ![Firebird](https://img.shields.io/badge/Firebird-E32929?style=for-the-badge&logo=firebird&logoColor=white) |
| **Testing** | ![Go test](https://img.shields.io/badge/Go_test-00ADD8?style=for-the-badge&logo=go&logoColor=white) ![Vitest](https://img.shields.io/badge/Vitest-6E9F19?style=for-the-badge&logo=vitest&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white) |
| **DevOps & Cloud** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-F80000?style=for-the-badge&logo=oracle&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) |

---

### 💼 Experience

**PerainsON Technology** — *Solo Software Developer*
*Since May 2026*

- Researched, architected, and built an **ERP for Brazilian accounting** from zero — schema, business rules, API, and UI.
- Implemented the **payroll workflow**: preview → findings → operator approval → confirm/cancel, with CSV export and audit trails.
- Built an **API-first backend** with go-chi, sqlc, pgx, and golang-migrate — TypeScript client generated from the OpenAPI spec with orval.
- Delivered a **typed React + TypeScript frontend** governed by a **design system of global tokens** (shadcn/Tailwind, light + dark, zero hardcoded colors), with Vitest unit tests and Playwright E2E.
- Established **CI (`make ci`)**: lint, tests, and build gates on every change.

**Campos Development** — *Software Development Intern*
*Dec 2025 — May 2026*

- Developed a **scalable marketplace / registry (notary) system** using **serverless microservices on AWS Lambda**.
- Built the **React frontend** and **Python backend**, with **Amazon Aurora PostgreSQL** provisioned via **DDL**.
- Worked on service decomposition and scalability in a microservice architecture.

---

### 🛠️ Featured Projects

#### [client-on](https://github.com/EmanuProds/client-on)
Customer service platform that organizes incoming **WhatsApp messages by department**.
`Next.js` `Express` `PostgreSQL` `Tailwind CSS` `Docker Compose` `whatsapp-web.js`

#### [image2file](https://github.com/EmanuProds/image2file)
**GTK4 desktop app** that converts document images into organized PDFs using **OCR (Tesseract)** — auto-detects page numbers, organizes the document, and allows manual correction when OCR fails.
`Python` `GTK4` `Tesseract OCR`

#### [archpi](https://github.com/EmanuProds/archpi) & [fedorapi](https://github.com/EmanuProds/fedorapi)
Shell toolkits that turn a fresh **Arch Linux** / **Fedora** install into a complete development workstation in minutes — dotfiles, packages, and configs fully automated.
`Bash` `Automation` · archpi ⭐ 3

---

### 🌐 Connect With Me

[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white)](https://emanuprods.github.io/about-me/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/emanuprods)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:emanuprods@proton.me)
