# Sergey Nikitchenko — Full-stack Developer (Python · Kotlin · React)

I build and maintain production web products end to end: domain model and API,
admin panels and storefronts, payments, CI/CD and deployment.
Open to freelance and contract work, fully remote.

## Recent commercial work

Most of my commercial code lives in private client repositories, so here is a summary.

**Platform with payments and an online store**

*Kotlin, Spring Boot, MariaDB · Nuxt, Vue 3, TypeScript · Docker, GitHub Actions*

- Built the financial core: transactions, gift certificates, refunds with bank status reconciliation, royalty and acquiring-fee calculations — all covered by tests.
- Designed and shipped the Shop module from scratch: domain model, API, admin, storefront, checkout with payment, customer notifications, permissions.
- Integrated acquiring behind an adapter and a feature flag — switching payment providers without touching business logic.
- Set up CI/CD for a monorepo: builds only changed subprojects, test gate before deploy, fast rollback, migration checks.
- Audited the codebase inherited from a previous team, wrote the spec and estimates for two milestones. 700+ commits — over half of the repository history.

**Photo platform with face search**

*Python, FastAPI, PostgreSQL, Redis · React, Next.js, TypeScript · Milvus, InsightFace · GitLab CI*

- Developed a five-service platform: BFF, image upload, selfie search over face embeddings, admin and client frontends.
- Ran a security audit of authentication and public APIs, delivered a prioritized report before release.
- Migrated payments to a new acquiring provider, reworked pricing with regional overrides.

**Corporate ERP (Galaktika)** — about a year

Business logic in VIP, SQL reporting and query optimization, FastReport print forms, automating manual accounting processes together with business stakeholders.

## Stack

- **Backend:** Python (FastAPI, Django/DRF, SQLAlchemy), Kotlin (Spring Boot)
- **Frontend:** React / Next.js, Vue / Nuxt, TypeScript, Tailwind CSS
- **Data:** PostgreSQL, MariaDB / MySQL, Redis
- **Infra:** Docker, GitHub Actions, GitLab CI
- **Also:** Telegram bots (aiogram), LLM integrations (OpenAI / OpenRouter)

## Background

Before development I spent 8 years in rail logistics, up to head of a logistics department — so I'm used to talking with business stakeholders and turning their processes into working software.

## How I work

- Small, reviewable milestones with a working demo at each step
- Tests and Docker from day one, so the project runs the same everywhere
- Human-in-the-loop for anything AI writes into real data
