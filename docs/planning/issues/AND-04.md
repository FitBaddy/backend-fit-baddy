---
id: AND-04
title: "[Android] Экран Quest: программы, сессия, история"
assignee: Soloveve
labels: [module:android, type:feature, sprint-2]
milestone: "Sprint 2"
status: done
story_points: 5
related_us: [US-B1, US-C2, US-C3]
---
## Что сделать
Тренировки в приложении.

## Детали / спецификация
- `mobile-fit-baddy/app/src/main/java/com/fitquest/app/ui/workout/WorkoutFragment.java`, `item_plan.xml`, `item_session.xml`; локальный секундомер в `SessionStore`, «Pin as today».


## Критерии готовности
- [x] `./gradlew testDebugUnitTest` и lint зелёные

## Зависимости
- [AND-01](AND-01.md) — [Android] Каркас приложения: Retrofit, сессия, навигация

## Вопросы
Нет открытых вопросов.
