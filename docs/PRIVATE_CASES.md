# Private systems · selected engineering case notes

> Обзор закрытых работ DizZy (октябрь 2026). Здесь нет исходного кода, секретов, клиентских данных, приватных адресов, ключей или недоказанных метрик. **PRIVATE** описывает доступ к репозиторию, а не коммерческую зрелость продукта.

## JANQOR — operational loss control plane
**Статус:** PRIVATE · активная подготовка пилотной инфраструктуры; подтвержденное клиентское внедрение не заявляется.

**Задача:** превращать разрозненные операционные события ресторанного бизнеса в проверяемую цепочку «сигнал → действие → доказательство → оценка результата».

**Инженерия:** FastAPI, async SQLAlchemy, PostgreSQL, Redis/Celery, tenant-scoped operator access, transactional outbox, audit trail, PostgreSQL E2E и telemetry/readiness. Детектирование основных SLA-событий детерминировано, без обязательного AI в критическом контуре.

## VINFLOW — vehicle operations and document workflow
**Статус:** PRIVATE · локальный CI-tested прототип пилота, **не production-ready**.

**Задача:** соединить поступление документов, извлечение данных, проверку оператором, учет автомобилей и контролируемое оформление сделки.

**Инженерия:** Python/FastAPI, PostgreSQL, OCR (в том числе Tesseract), обработка PDF, хранение оригиналов, дедупликация, ручное подтверждение, аудит и контейнерные smoke-тесты. Интеграции и юридические операции не заявляются работающими там, где они еще не реализованы/не проверены.

## Catoku — Telegram logic game
**Статус:** PRIVATE · активно развиваемая Telegram Mini App.

**Задача:** превратить короткую логическую головоломку в систему с долгосрочным прогрессом и повторяемыми активностями.

**Инженерия:** FastAPI, aiogram, PostgreSQL, верификация Telegram WebApp initData, генерация и проверка задач, сезонные и ежедневные механики, UX для мобильных клиентов.

**Публичная точка входа:** [@catoku_bot](https://t.me/catoku_bot).

## ISLUMI — living islands
**Статус:** PRIVATE · играбельная тестовая версия, не публичный релиз.

**Задача:** процедурные персональные острова, экспедиции, коллекции и долговременное состояние мира.

**Инженерия:** React/TypeScript/Vite, FastAPI, PostgreSQL/SQLAlchemy, миграции, Telegram authentication, CI и раздельное управление client/server state.

## PokéHub / Raid Lab — Telegram game platform
**Статус:** PRIVATE · итерационная разработка.

**Задача:** согласованное состояние коллекций, рейдов, breeding и Mini App при параллельных действиях пользователей.

**Инженерия:** Python/aiogram, async SQLAlchemy, PostgreSQL-authoritative state, миграции, серверные операции и защита от повторного создания/списания ресурсов при двойных кликах.

---

## Публичные инженерные доказательства

- [Sentinel](https://github.com/DizzyZ7/Sentinel) — воспроизводимый security demo, gate перед исправлением, evidence и human review.
- [StormRelay](https://github.com/DizzyZ7/StormRelay) — at-least-once events, durable runbooks, RBAC/OIDC и OpenTelemetry.
- [ChainScribe API](https://github.com/DizzyZ7/ChainScribe-API) — auth boundaries, immutability, rate limiting и CI.
- [SignalBox](https://github.com/DizzyZ7/SignalBox) — durable webhook gateway, replay, HMAC и SSRF guard.
- [DizZy Systems Atlas](https://github.com/DizzyZ7/DizZy-Systems-Atlas) — навигация по портфолио и проверяемые сведения о системах.

**Принцип:** никаких выдуманных пользователей, денежных результатов, uptime или утверждений о production, если это не подтверждается фактами.

[← К профилю](../README.md)
