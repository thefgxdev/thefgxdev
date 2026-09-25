<h1 align="center">Felipe Guedes</h1>
<p align="center"><b>Software Engineer · Systems Architect · System Design</b></p>
<p align="center">Full stack in the literal sense: front end, back end and the infrastructure underneath.<br>600+ systems built, reviewed or audited across ten years and 19 countries. The failure that nobody finds is the one I look for.</p>
<p align="center">
  <a href="https://fgxdev.com">fgxdev.com</a> ·
  <a href="https://fgxdev.com/services/">services</a> ·
  <a href="https://fgxdev.com/articles/">150+ articles</a> ·
  <a href="https://www.linkedin.com/in/fgxdev">LinkedIn</a> ·
  <a href="https://x.com/thefgxdev">X</a> ·
  <a href="mailto:contato@fgxdev.com">contato@fgxdev.com</a>
</p>
<p align="center">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-strict-3178C6?logo=typescript&logoColor=white">
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-App%20Router-000000?logo=nextdotjs&logoColor=white">
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-20+-339933?logo=nodedotjs&logoColor=white">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white">
  <img alt="Cloudflare" src="https://img.shields.io/badge/Cloudflare-F38020?logo=cloudflare&logoColor=white">
  <img alt="AWS" src="https://img.shields.io/badge/AWS-232F3E?logo=amazonwebservices&logoColor=white">
  <img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black">
</p>

---

## Featured · faultline

> **Find the failure nobody finds.** Six hundred systems taught me one sentence: the failure is in a boundary someone trusted. [faultline](https://github.com/thefgxdev/faultline) reads those boundaries for you before the review starts: outbound calls without timeouts, retries without backoff, money endpoints without idempotency keys, swallowed errors, SQL and shell built from strings, secrets in code, cookies without flags, queries that forget the tenant. Zero dependencies, one command, a report with the fix for every finding, an exit code for CI and a GitHub Action.
>
> ```bash
> npx github:thefgxdev/faultline . --fail-on high
> ```
>
> [Read the rules →](https://github.com/thefgxdev/faultline/blob/main/docs/rules.md) · [Star it if it found something ★](https://github.com/thefgxdev/faultline)

## What I do

| | |
|---|---|
| **System Design & architecture** | How a system is organised, scales and fails safely, decided before the first line of code. Domain boundaries, data ownership, queues, idempotency, multi-tenancy, capacity, reversible migrations. [→ architecture](https://fgxdev.com/software-architecture-system-design/) |
| **Audits** | Code, architecture, infrastructure and application-security reviews that find the race condition in the payment, the permission that leaks data between tenants, the backup nobody ever restored. Written report, ordered by impact. [→ audits](https://fgxdev.com/software-audit-security/) |
| **Full-stack delivery** | Products that have to last: Next.js, TypeScript, Node.js, PostgreSQL, with Linux, Cloudflare and AWS underneath. Deploy pipelines, observability and incident response as part of the delivery, not as extras. [→ development](https://fgxdev.com/software-development-cascavel/) |
| **AI in production** | Agents, RAG, evals and guardrails shipped as systems with an accountable human, not as demos. Eleven agents run a news portal every day under human editorial responsibility. [→ production AI](https://fgxdev.com/ai-for-companies/) |

## Building now

| Project | What it is | Role |
|---|---|---|
| **ELUCENIA** · [elucenia.org](https://elucenia.org) | A global medical and scientific network to accelerate discovery. Every hypothesis needs evidence, every advance needs validation, every decision needs a human who answers for it. What it does stays inside the lab until it is validated. | Founder, Systems Architect |
| **NextFoot** | A football game built from the engine up: match simulation, real-time state, multiplayer-ready architecture. | Creator, Systems Architect |
| **Cravamos** · [cravamos.com.br](https://cravamos.com.br) | News and services portal run by eleven specialised AI agents under human editorial responsibility, with identified sources. | Founder, Architect |
| **Facívia** | Multi-tenant CRM for B2B operations: pipeline, accounts, automation, integrations. | Systems Architect, Lead Engineer |
| **Klic.bio** | Web platform for entrepreneurs: multi-tenant, automated SEO, edge delivery, a publishing flow a non-technical owner runs alone. | Founder, Architect |
| **FGX Web** | Engineering and security backbone behind the group's products: cloud architecture, hardening, CI/CD, observability, incident response. | Principal Engineer |

## How I work

- **First conversation, first diagnosis.** Give me any company and, on the first call, I will tell you what its systems need and where they are going to break.
- **Written scope, dated deliverables, acceptance criteria.** No surprise at the end, because the scope was written at the start.
- **The team keeps the knowledge.** Architecture decision records, documentation, review sessions until everyone agrees with the decisions. Code stays in your repository.
- **Zero failures I am comfortable ignoring.** Every known failure gets an owner.

## Open source

Documentation, checklists, templates and tools from the same practice. Documentation under Apache-2.0; faultline under AGPL-3.0. Authorship preserved in every file.

| Repository | What it is |
|---|---|
| [faultline](https://github.com/thefgxdev/faultline) | **Find the failure nobody finds.** Zero-dependency auditor for the boundaries in a codebase: timeouts, retries, idempotency, swallowed errors, injection, secrets, cookies, tenant isolation. `npx github:thefgxdev/faultline .` |
| [system-design-playbook](https://github.com/thefgxdev/system-design-playbook) | Patterns and decision records: outbox, idempotency, multi-tenancy, capacity, migrations, degradation |
| [architecture-review-checklist](https://github.com/thefgxdev/architecture-review-checklist) | The twelve review questions, code/infra/security/privacy checklists, audit report template |
| [production-ai-checklist](https://github.com/thefgxdev/production-ai-checklist) | RAG, agents, evals, guardrails, privacy, cost: what makes an AI feature work on Monday |
| [postgres-operations-runbook](https://github.com/thefgxdev/postgres-operations-runbook) | Backups you restored, migrations without locks, performance, hot partitions, first fifteen minutes |
| [incident-response-runbook](https://github.com/thefgxdev/incident-response-runbook) | Severity, roles, first fifteen minutes, communication templates, blameless postmortems |
| [nextjs-app-router-patterns](https://github.com/thefgxdev/nextjs-app-router-patterns) | Server/client boundary, safe server actions, caching, errors, structure |
| [web-security-headers](https://github.com/thefgxdev/web-security-headers) | CSP, HSTS and friends for Apache, Nginx, Cloudflare and Next.js |
| [seo-aeo-audit](https://github.com/thefgxdev/seo-aeo-audit) | Zero-dependency static-site audit and a guide to llms.txt and answer engines |
| [adr-tools](https://github.com/thefgxdev/adr-tools) | Architecture Decision Records: template, examples, CLI |
| [awesome-system-design](https://github.com/thefgxdev/awesome-system-design) | Curated resources, one line on why for each |

## Selected writing

Notes on System Design, architecture, security, AI in production and science, in English and Portuguese. [All 150+ articles →](https://fgxdev.com/articles/)

- [The twelve questions I ask in every architecture review](https://fgxdev.com/articles/the-architecture-review-questions-i-always-ask/)
- [Exactly-once is a promise nobody keeps](https://fgxdev.com/articles/exactly-once-is-a-promise-nobody-keeps/)
- [Auditing a system you did not build, without offending the people who did](https://fgxdev.com/articles/auditing-a-system-you-did-not-build/)
- [The hot partition problem and why sharding does not save you](https://fgxdev.com/articles/the-hot-partition-problem/)
- [When to add a message broker, and when you are avoiding a decision](https://fgxdev.com/articles/when-to-add-a-message-broker/)
- [Postgres is enough, until the day it is not, and how to know that day](https://fgxdev.com/articles/postgres-is-enough-until-it-is-not/)
- [RAG is a data pipeline with a language model at the end](https://fgxdev.com/articles/rag-is-a-data-pipeline/)
- [Technical debt is a loan, and every loan has a name on it](https://fgxdev.com/articles/technical-debt-is-a-loan-with-a-name/)
- [Why I keep choosing Next.js for products that have to last](https://fgxdev.com/articles/why-i-keep-choosing-nextjs/)
- [Building world-class systems from a small city in Paraná](https://fgxdev.com/articles/building-from-a-small-city/)

## Background

Son of Dr. Pedro Moretti Guedes, a physician who treated for free those who could not pay; I maintain [his memorial](https://pedromorettiguedes.com.br). Raised by seven mothers, working since I was nine, self-taught in a print shop, on an electronics bench and in six hundred production systems. [The whole story →](https://fgxdev.com/life/)

Based in Toledo, Paraná, Brazil. On site in western Paraná, São Paulo and the Brazilian capitals; remote anywhere. Portuguese and English.

<details>
<summary><b>Em português</b></summary>

Engenheiro de Software e Arquiteto de Sistemas, especialista em System Design. Full stack no sentido literal: front-end, back-end e a infraestrutura por baixo. Mais de 600 sistemas construídos, revisados ou auditados em dez anos e 19 países. Conduzo a FGXDEV em Toledo, Paraná, e atendo Cascavel, o oeste do Paraná, São Paulo e as capitais presencialmente, e o mundo todo remotamente.

Construo a ELUCENIA, uma cadeia médica e científica global para acelerar a descoberta; o NextFoot, um jogo de futebol em simulação em tempo real; e a Cravamos, um portal em que onze agentes de IA publicam sob responsabilidade editorial humana.

[fgxdev.com/pt](https://fgxdev.com/pt/) · [serviços](https://fgxdev.com/pt/services/) · [artigos](https://fgxdev.com/pt/articles/) · contato@fgxdev.com
</details>
