<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:07111f,48:0f766e,100:7cf7c4&text=Dimash%20%22DizZy%22%20Janibekov&fontColor=ffffff&fontSize=42&fontAlignY=36&desc=Senior%20Backend%20%C2%B7%20Integrations%20%C2%B7%20Automation%20%C2%B7%20Reliable%20Systems&descAlignY=58&descSize=17" />

<div align="center">

### Превращаю сложные бизнес-процессы и ненадежные интеграции в системы, которые можно развернуть, наблюдать, сопровождать и восстанавливать.

<p>
  <a href="https://dizzyz7.github.io/dimashjanibekov.github.io/"><img src="https://img.shields.io/badge/ПОРТФОЛИО-ОТКРЫТЬ-7cf7c4?style=for-the-badge&labelColor=07111f" /></a>
  <a href="https://t.me/dizzy_dev"><img src="https://img.shields.io/badge/Telegram-@dizzy__dev-14b8a6?style=for-the-badge&logo=telegram&logoColor=white" /></a>
  <a href="mailto:dizzyod.z7@gmail.com"><img src="https://img.shields.io/badge/Email-dizzyod.z7%40gmail.com-0f766e?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

<p>
  <img src="https://komarev.com/ghpvc/?username=DizzyZ7&label=Просмотры%20профиля&color=0f766e&style=for-the-badge" />
</p>

<p>
  <img src="https://img.shields.io/badge/3%2B%20года-коммерческой%20разработки-0f766e?style=flat-square" />
  <img src="https://img.shields.io/badge/Санкт--Петербург-Россия-14b8a6?style=flat-square" />
  <img src="https://img.shields.io/badge/Формат-remote%20%7C%20hybrid%20%7C%20office-0f766e?style=flat-square" />
  <img src="https://img.shields.io/badge/Фокус-backend%20%7C%20integration%20%7C%20platform-14b8a6?style=flat-square" />
</p>

</div>

---

## Профиль

Я **Senior Backend / Integration & Automation Engineer** с 3+ годами коммерческого опыта и самостоятельной инженерной практикой с 2019 года.

Моя сильная зона — участок между бизнес-требованием и реальной эксплуатацией: **Python backend, PostgreSQL, REST/OpenAPI, webhooks, асинхронная обработка, внешние интеграции, надежность, observability и владение результатом после релиза**.

Работал с внутренней **MedTech-платформой**, координировал техническую работу команды из 6 человек и развивал интеграционные/автоматизационные процессы для **пяти ресторанных сетей** — CRM, helpdesk, 1С, loyalty-платформы, Telegram, формы, SMS и внешние API. В выделенных типовых процессах доля автоматизированной обработки достигала **до 87%**.

Параллельно развиваю публичные production-oriented проекты на Go, TypeScript и AI/RAG, когда они усиливают продукт и backend-архитектуру, а не подменяют ее.

**Лучшее совпадение по ролям:** Senior Python Backend, Backend / Integration, Platform / Internal Tools, Automation, AI Backend, event-driven и reliability-heavy продуктовые команды.

---

## Что умею закрывать end-to-end

<table>
<tr>
<td width="50%" valign="top">

### Backend и данные

- Python, FastAPI, asyncio, SQLAlchemy, Alembic, Pydantic
- Django / Django Ninja / Flask — проектная и прикладная практика
- PostgreSQL, Redis, SQL, JSON/JSONB, migrations, indexes
- Доменная модель, транзакции, row locking, жизненный цикл данных
- REST/OpenAPI, webhooks, WebSocket, внешние API

</td>
<td width="50%" valign="top">

### Надежность и распределенные сценарии

- Idempotency, deduplication, retries/backoff, replay
- Durable queues, transactional outbox, at-least-once semantics
- Rate limiting, timeouts, DLQ-style failure handling
- Audit trail, correlation IDs, graceful shutdown
- Health/readiness checks, runbooks, recovery paths

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Security и observability

- JWT, opaque tokens, RBAC/OIDC, access-control boundaries
- HMAC signatures, token hashing, input validation, SSRF protection
- Prometheus, Grafana, OpenTelemetry, structured JSON logging
- CodeQL, Trivy, pip-audit, security-oriented CI
- OWASP-aware backend design и least-trust интеграции

</td>
<td width="50%" valign="top">

### Delivery и продуктовая инженерия

- Docker, Docker Compose, Linux, Nginx, GitHub Actions, GHCR
- Pytest, unittest, Playwright, API/DB/E2E и smoke testing
- Требования, декомпозиция, AS-IS/TO-BE, BPMN, API contracts
- Техническая документация, ADR, release/support ownership
- Go, TypeScript/Next.js/React и PHP/Yii2 в отдельных проектах

</td>
</tr>
</table>

---

## Флагманские инженерные системы

| Проект | Что показывает | Стек |
| --- | --- | --- |
| **JANQOR** *(активный private-продукт)* | Operational control plane для выявления бизнес-потерь, запуска управляемых действий, сбора доказательств и измерения recovered value. Первый вертикальный рынок — рестораны. Multi-tenant boundaries, operator credentials, transactional outbox, readiness/telemetry и PostgreSQL E2E. | Python · FastAPI · SQLAlchemy async · PostgreSQL · Redis · Celery |
| **[ChainScribe API](https://github.com/DizzyZ7/ChainScribe-API)** | Security-focused backend с dual auth, Argon2, token hashing, ownership enforcement, row locks, immutable audit events, Redis rate limiting и production CI. | Python · Django Ninja · PostgreSQL · Redis · Docker |
| **[StormRelay](https://github.com/DizzyZ7/StormRelay)** | Event-correlation / incident-response control plane с at-least-once processing, JetStream, durable runbooks, RBAC/OIDC и tracing через async boundaries. | Go · PostgreSQL · NATS JetStream · OpenTelemetry |
| **[SignalBox](https://github.com/DizzyZ7/SignalBox)** | Webhook gateway с durable PostgreSQL queue, deduplication, replay, HMAC forwarding, SSRF guard, Prometheus metrics и security CI. | Go · PostgreSQL · OpenAPI · Docker |
| **[Intelligent Support Orchestrator](https://github.com/DizzyZ7/Intelligent-Support-Orchestrator-with-RAG-Async-Processing)** | RAG-backend, где ingestion/retrieval/LLM-нагрузка отделена от синхронного API path и выполняется background workers. | Python · FastAPI · Celery · Redis · Qdrant · LangChain |
| **[WTF / Work Task Flow](https://github.com/DizzyZ7/WTF_Tast_Manager)** | Self-hosted task/project platform с независимым от транспорта domain core, PostgreSQL persistence, REST/OpenAPI и realtime collaboration. | TypeScript · Next.js · PostgreSQL · WebSocket/Yjs · Docker |
| **[QA Microservices E2E](https://github.com/DizzyZ7/qa-microservices-e2e-playwright-py)** | Проверяемые state transitions по цепочке API → UI → PostgreSQL, изолированные test data, cleanup, traces/screenshots, Allure и CI. | Python · Pytest · Playwright · PostgreSQL · Docker |
| **[HomeLedger](https://github.com/DizzyZ7/home-ledger)** | Self-hosted продукт с Flutter-клиентом и FastAPI backend, JWT, migrations, tests и явными mobile/backend boundaries. | Flutter · FastAPI · PostgreSQL · SQLAlchemy · Docker |

<details>
<summary><b>Еще выбранные проекты</b></summary>

<br />

- **[AI Ticket Agent](https://github.com/DizzyZ7/ai-ticket-agent)** — FastAPI-сервис классификации обращений, определения приоритета и подготовки черновика ответа с PostgreSQL, Redis и явной обработкой дублей.
- **[TelcoNet Guardian](https://github.com/DizzyZ7/TelcoNet-Guardian)** — async network monitoring, SLA tracking, Prometheus/Grafana и operational alerts.
- **[Dodo CV Table Detector](https://github.com/DizzyZ7/dodo-cv-table-detector)** — lightweight OpenCV pipeline для определения состояния зон через ROI/background modeling и event timeline.
- **[SME Cashflow Copilot](https://github.com/DizzyZ7/sme-cashflow-copilot)** — forecasting и what-if decision support на FastAPI/Pandas с audit-friendly результатами.
- **[WorkNest API](https://github.com/DizzyZ7/worknest-api)** — компактный FastAPI/PostgreSQL сервис с SQLAlchemy, Alembic, Docker и Pytest.

</details>

---

## Коммерческий опыт — кратко

**Независимая разработка / самозанятость — Senior Backend / Automation Engineer, 2026 — настоящее время**  
Production-oriented backend, интеграционные и automation-системы. Текущий фокус — JANQOR и публичные инженерные проекты с надежной обработкой событий, security boundaries, тестированием, CI/CD и observability.

**ООО «МЕДКЛИК» — Backend & Integration Engineer, октябрь 2025 — январь 2026**  
Внутренняя MedTech-платформа: Python/PHP/Yii2, PostgreSQL/SQL, REST API, webhooks. Анализ требований, надежный обмен данными, production diagnostics и восстановление сервисов. Техническая координация команды из **6 человек**.

**ИП ЮР Е.В. / ООО «ПРОФИТЭНДХОРЕКА» — Integration & Automation Engineer, ноябрь 2023 — октябрь 2025**  
Интеграционный контур **пяти ресторанных сетей**: Usedesk, Mindbox, LoyaltyPlant, CRM, 1С, Telegram, формы, SMS и внешние API. Python-автоматизации, routing/SLA, BPMN и устойчивость к дублям, rate limits и partial failures. До **87% выделенных типовых сценариев** переведено в автоматизированный контур.

**Техфорвард — Python Developer, декабрь 2022 — ноябрь 2023**  
Backend-компоненты кроссплатформенного аналитического приложения: сбор, обработка и агрегация данных, внутренние API, аналитика и GitHub Actions release-сборки для Windows, macOS и Linux.

---

## Инженерный подход

```text
Понять бизнес-инвариант
        ↓
Определить домен и API-контракт
        ↓
Спроектировать failure semantics, а не только happy path
        ↓
Реализовать транзакции / idempotency / observability
        ↓
Проверить state transitions между границами системы
        ↓
Развернуть, мониторить, диагностировать и восстанавливать
```

Предпочитаю **modular monolith**, когда его достаточно. Микросервисы использую только тогда, когда независимое владение, масштабирование или изоляция отказов действительно оправдывают дополнительную операционную сложность. При модернизации legacy предпочитаю постепенное выделение компонентов и четкие контракты вместо рискованного полного rewrite.

---

## AI / RAG как backend-компетенция

Использую LLM как контролируемый компонент внутри программной системы, а не как замену детерминированной бизнес-логики.

Типовые паттерны в моих проектах:

- ingestion базы знаний, embeddings и vector retrieval;
- structured output и schema validation;
- background execution, retries и idempotency;
- human-review или deterministic decision layer там, где цена ошибки высока;
- PostgreSQL / Qdrant / pgvector и отслеживаемый source context;
- интеграция через FastAPI, Docker deployment и operational monitoring.

---

## Образование и языки

- **СПбПУ Петра Великого** — Институт компьютерных наук и кибербезопасности, «Информационные системы и технологии», заочно, 2023 — настоящее время.
- **1 место**, инженерный трек Кейс-чемпионата Петра Великого — концепция автономного промышленного TTS/STT-модуля для систем оповещения.
- Русский — родной · English — B2 · Čeština — B2 · Deutsch — A2.

---

## Контакты

<div align="center">

**Открыт к ролям Backend, Integration, Platform, Automation и AI Backend.**

<a href="https://dizzyz7.github.io/dimashjanibekov.github.io/"><img src="https://img.shields.io/badge/Портфолио-Смотреть%20проекты-7cf7c4?style=for-the-badge&labelColor=07111f" /></a>
<a href="https://t.me/dizzy_dev"><img src="https://img.shields.io/badge/Telegram-@dizzy__dev-14b8a6?style=for-the-badge&logo=telegram&logoColor=white" /></a>
<a href="mailto:dizzyod.z7@gmail.com"><img src="https://img.shields.io/badge/Email-dizzyod.z7%40gmail.com-0f766e?style=for-the-badge&logo=gmail&logoColor=white" /></a>

<br /><br />

**Санкт-Петербург · +7 (999) 521-28-81 · github.com/DizzyZ7**

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:07111f,48:0f766e,100:7cf7c4" />