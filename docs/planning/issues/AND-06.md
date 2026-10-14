---
id: AND-06
title: "[Android] Live watch: WebSocket и запасной REST"
assignee: Soloveve
labels: [module:android, type:feature, sprint-2]
milestone: "Sprint 2"
status: done
story_points: 3
related_us: [US-H1]
---
## Что сделать
Живые пульс и шаги, переход на опрос при обрыве.

## Детали / спецификация
- `mobile-fit-baddy/app/src/main/java/com/fitquest/app/ws/TelemetryWebSocket.java`, `ui/telemetry/TelemetryFragment.java`: регистрация устройства, «Simulate beat», история, статус соединения.


## Критерии готовности
- [x] `./gradlew testDebugUnitTest` и lint зелёные

## Зависимости
- [AND-01](AND-01.md) — [Android] Каркас приложения: Retrofit, сессия, навигация

## Вопросы
Нет открытых вопросов.
