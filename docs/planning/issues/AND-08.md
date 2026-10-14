---
id: AND-08
title: "[Android] Офлайн-кэш последней точки и статус с датой"
assignee: Soloveve
labels: [module:android, type:feature, sprint-4]
milestone: "Sprint 4"
status: todo
story_points: 2
related_us: [US-H1]
---
## Что сделать
AC12.5–12.6.

## Детали / спецификация
- Кэш последней `TelemetryDto` в `SharedPreferences` (JSON); статус «офлайн, последнее известное · 14:32».
- Логика выбора источника — чистый класс `mobile-fit-baddy/app/src/main/java/com/fitquest/app/ws/TelemetrySourcePolicy.java` с unit-тестом.


## Критерии готовности
- [ ] `./gradlew testDebugUnitTest` и lint зелёные

## Зависимости
- [AND-06](AND-06.md) — [Android] Live watch: WebSocket и запасной REST

## Вопросы
Нет открытых вопросов.
