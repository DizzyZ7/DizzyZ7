<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:07111f,48:0f766e,100:7cf7c4&text=Dimash%20%22DizZy%22%20Janibekov&fontColor=ffffff&fontSize=42&fontAlignY=36&desc=Senior%20Backend%20%C2%B7%20Integrations%20%C2%B7%20Automation%20%C2%B7%20Reliable%20Systems&descAlignY=58&descSize=17" />

<div align="center">

### I turn messy business processes and unreliable integrations into systems that can be deployed, observed and recovered.

<p>
  <a href="https://dizzyz7.github.io/dimashjanibekov.github.io/"><img src="https://img.shields.io/badge/PORTFOLIO-OPEN-7cf7c4?style=for-the-badge&labelColor=07111f" /></a>
  <a href="https://t.me/dizzy_dev"><img src="https://img.shields.io/badge/Telegram-@dizzy__dev-14b8a6?style=for-the-badge&logo=telegram&logoColor=white" /></a>
  <a href="mailto:dizzyod.z7@gmail.com"><img src="https://img.shields.io/badge/Email-dizzyod.z7%40gmail.com-0f766e?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

<p>
  <img src="https://img.shields.io/badge/3%2B%20years-commercial%20engineering-0f766e?style=flat-square" />
  <img src="https://img.shields.io/badge/Saint%20Petersburg-Russia-14b8a6?style=flat-square" />
  <img src="https://img.shields.io/badge/Format-remote%20%7C%20hybrid%20%7C%20on--site-0f766e?style=flat-square" />
  <img src="https://img.shields.io/badge/Focus-backend%20%7C%20integration%20%7C%20platform-14b8a6?style=flat-square" />
</p>

</div>

---

## Profile

I am a **Senior Backend / Integration & Automation Engineer** with 3+ years of commercial experience and independent engineering practice since 2019.

My strongest area is the space between business requirements and production reality: **Python backend, PostgreSQL, REST/OpenAPI, webhooks, asynchronous processing, external integrations, reliability, observability and operational ownership**.

I have worked on an internal **MedTech platform**, coordinated technical delivery for a team of 6, and built integration/automation workflows for **five restaurant chains** across CRM, helpdesk, 1C, loyalty platforms, Telegram, forms and external APIs. In selected recurring workflows, automation reached **up to 87% of typical support/operational scenarios**.

I also build public production-style systems in Go, TypeScript and AI/RAG when they strengthen the product rather than distract from the backend core.

**Best fit:** Senior Python Backend, Backend / Integration, Platform / Internal Tools, Automation, AI Backend, event-driven and reliability-heavy product roles.

---

## What I own end to end

<table>
<tr>
<td width="50%" valign="top">

### Backend & data

- Python, FastAPI, asyncio, SQLAlchemy, Alembic, Pydantic
- Django / Django Ninja / Flask — project and applied experience
- PostgreSQL, Redis, SQL, JSON/JSONB, migrations and indexes
- Domain models, transactions, row locking and data lifecycle
- REST/OpenAPI, webhooks, WebSocket and external APIs

</td>
<td width="50%" valign="top">

### Reliability & distributed flows

- Idempotency, deduplication, retries/backoff and replay
- Durable queues, transactional outbox and at-least-once semantics
- Rate limiting, timeouts, DLQ-style failure handling
- Audit trails, correlation IDs and graceful shutdown
- Health/readiness checks, runbooks and recovery paths

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Security & observability

- JWT, opaque tokens, RBAC/OIDC and access-control boundaries
- HMAC signatures, token hashing, input validation and SSRF protection
- Prometheus, Grafana, OpenTelemetry and structured JSON logging
- CodeQL, Trivy, pip-audit and security-oriented CI checks
- OWASP-aware backend design and least-trust integration patterns

</td>
<td width="50%" valign="top">

### Delivery & product engineering

- Docker, Docker Compose, Linux, Nginx, GitHub Actions and GHCR
- Pytest, unittest, Playwright, API/DB/E2E and smoke testing
- Requirements, decomposition, AS-IS/TO-BE, BPMN and API contracts
- Technical documentation, ADRs, release/support ownership
- Go, TypeScript/Next.js/React and PHP/Yii2 in selected projects

</td>
</tr>
</table>

---

## Flagship engineering systems

| Project | What it proves | Stack |
| --- | --- | --- |
| **JANQOR** *(active private product)* | Operational control plane for detecting business losses, governed actions, evidence and recovered-value measurement; restaurant vertical first. Multi-tenant boundaries, operator credentials, transactional outbox, readiness/telemetry and PostgreSQL E2E. | Python · FastAPI · SQLAlchemy async · PostgreSQL · Redis · Celery |
| **[ChainScribe API](https://github.com/DizzyZ7/ChainScribe-API)** | Security-focused publishing backend with dual auth, Argon2, token hashing, ownership enforcement, row locks, immutable audit events, Redis rate limiting and production CI. | Python · Django Ninja · PostgreSQL · Redis · Docker |
| **[StormRelay](https://github.com/DizzyZ7/StormRelay)** | Event-correlation and incident-response control plane with at-least-once processing, JetStream, durable runbooks, RBAC/OIDC and traces across async boundaries. | Go · PostgreSQL · NATS JetStream · OpenTelemetry |
| **[SignalBox](https://github.com/DizzyZ7/SignalBox)** | Compact webhook gateway with durable PostgreSQL queue, deduplication, replay, HMAC forwarding, SSRF guard, Prometheus metrics and security CI. | Go · PostgreSQL · OpenAPI · Docker |
| **[Intelligent Support Orchestrator](https://github.com/DizzyZ7/Intelligent-Support-Orchestrator-with-RAG-Async-Processing)** | RAG backend where ingestion/retrieval/LLM work is separated from the synchronous API path and processed through background workers. | Python · FastAPI · Celery · Redis · Qdrant · LangChain |
| **[WTF / Work Task Flow](https://github.com/DizzyZ7/WTF_Tast_Manager)** | Self-hosted task/project platform with a transport-independent domain core, PostgreSQL persistence, REST/OpenAPI and realtime collaboration. | TypeScript · Next.js · PostgreSQL · WebSocket/Yjs · Docker |
| **[QA Microservices E2E](https://github.com/DizzyZ7/qa-microservices-e2e-playwright-py)** | Verifiable API → UI → PostgreSQL state transitions, isolated test data, cleanup, traces/screenshots, Allure and CI. | Python · Pytest · Playwright · PostgreSQL · Docker |
| **[HomeLedger](https://github.com/DizzyZ7/home-ledger)** | Self-hosted product with Flutter client + FastAPI backend, JWT, migrations, tests and clear mobile/backend boundaries. | Flutter · FastAPI · PostgreSQL · SQLAlchemy · Docker |

<details>
<summary><b>More selected work</b></summary>

<br />

- **[AI Ticket Agent](https://github.com/DizzyZ7/ai-ticket-agent)** — FastAPI service for ticket categorization, priority and draft replies with PostgreSQL, Redis and explicit duplicate handling.
- **[TelcoNet Guardian](https://github.com/DizzyZ7/TelcoNet-Guardian)** — async network monitoring, SLA tracking, Prometheus/Grafana and operational alerts.
- **[Dodo CV Table Detector](https://github.com/DizzyZ7/dodo-cv-table-detector)** — lightweight OpenCV occupancy-state pipeline using ROI/background modeling and event timelines.
- **[SME Cashflow Copilot](https://github.com/DizzyZ7/sme-cashflow-copilot)** — forecasting and what-if decision support with FastAPI, Pandas and auditable outputs.
- **[WorkNest API](https://github.com/DizzyZ7/worknest-api)** — focused FastAPI/PostgreSQL service with SQLAlchemy, Alembic, Docker and Pytest.

</details>

---

## Commercial experience — short version

**Independent / self-employed — Senior Backend / Automation Engineer, 2026–present**  
Production-oriented backend, integration and automation systems; current focus includes JANQOR and public engineering systems with reliable event processing, security boundaries, tests, CI/CD and observability.

**MedClick — Backend & Integration Engineer, Oct 2025–Jan 2026**  
Internal MedTech platform on Python/PHP/Yii2, PostgreSQL/SQL, REST APIs and webhooks. Requirements/decomposition, reliable data exchange, production diagnostics and service recovery. Technical coordination for a **6-person team**.

**PROFITENDHOREKA / IP YUR E.V. — Integration & Automation Engineer, Nov 2023–Oct 2025**  
Integration layer for **five restaurant chains** across Usedesk, Mindbox, LoyaltyPlant, CRM, 1C, Telegram, forms, SMS and external APIs. Python automation, routing/SLA, BPMN and resilient handling of duplicates, rate limits and partial failures. Up to **87% of selected recurring scenarios** moved into an automated flow.

**Techforward — Python Developer, Dec 2022–Nov 2023**  
Backend components for a cross-platform analytics application: collection, processing, aggregation, internal APIs and GitHub Actions release builds for Windows, macOS and Linux.

---

## Engineering principles

```text
Understand the business invariant
        ↓
Define the domain and API contract
        ↓
Design failure semantics, not only the happy path
        ↓
Build with transactions / idempotency / observability
        ↓
Test state transitions across boundaries
        ↓
Deploy, monitor, diagnose and recover
```

I prefer a modular monolith when it is enough, and microservices only when independent ownership, scaling or failure isolation justify the operational cost. For legacy modernization I favor gradual extraction and explicit contracts over a risky full rewrite.

---

## AI / RAG as a backend capability

I use LLMs as controlled components inside software systems rather than as a replacement for deterministic business logic.

Typical patterns in my projects:

- knowledge-base ingestion, embeddings and vector retrieval;
- structured output and schema validation;
- background execution and retries;
- human-review or deterministic decision layers where risk matters;
- PostgreSQL/Qdrant/pgvector persistence and traceable source context;
- FastAPI integration, Docker deployment and operational monitoring.

---

## Education & languages

- **Peter the Great St. Petersburg Polytechnic University** — Institute of Computer Science and Cybersecurity, Information Systems and Technologies, part-time, 2023–present.
- **1st place**, Peter the Great Engineering Case Championship — autonomous industrial TTS/STT emergency-notification module concept.
- Russian — native · English — B2 · Czech — B2 · German — A2.

---

## Contact

<div align="center">

**Open to backend, integration, platform, automation and AI-backend roles.**

<a href="https://dizzyz7.github.io/dimashjanibekov.github.io/"><img src="https://img.shields.io/badge/Portfolio-View%20work-7cf7c4?style=for-the-badge&labelColor=07111f" /></a>
<a href="https://t.me/dizzy_dev"><img src="https://img.shields.io/badge/Telegram-@dizzy__dev-14b8a6?style=for-the-badge&logo=telegram&logoColor=white" /></a>
<a href="mailto:dizzyod.z7@gmail.com"><img src="https://img.shields.io/badge/Email-dizzyod.z7%40gmail.com-0f766e?style=for-the-badge&logo=gmail&logoColor=white" /></a>

<br /><br />

**Saint Petersburg · +7 (999) 521-28-81 · github.com/DizzyZ7**

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:07111f,48:0f766e,100:7cf7c4" />