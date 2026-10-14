---
id: AND-09
title: "[Android] Подключение узла Pi и индикация источника данных"
assignee: Soloveve
labels: [module:android, type:feature, sprint-5]
milestone: "Sprint 5"
status: todo
story_points: 2
related_us: [US-H1]
---
## Что сделать
Показать `device_token` для `.env` узла и метку «Симулятор / Raspberry Pi».

## Детали / спецификация
- Метка «Симулятор» / «Raspberry Pi» по полю `source`.

## Критерии готовности
- [ ] `./gradlew testDebugUnitTest` и lint зелёные

## Зависимости
- [BE-13](BE-13.md) — [Backend] Приём телеметрии от Pi: POST /telemetry/ingest с X-Device-Token

## Вопросы
Нет открытых вопросов.
