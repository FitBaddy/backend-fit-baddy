---
id: AND-07
title: "[Android] Unit-тесты и CI-job"
assignee: Soloveve
labels: [module:android, type:test, sprint-3]
milestone: "Sprint 3"
status: done
story_points: 2
related_us: [US-A1]
---
## Что сделать
JUnit без эмулятора и job `mobile` в CI.

## Детали / спецификация
- `AuthValidator` вынесен из `AuthActivity`; тесты `AuthValidatorTest`, `DtoParsingTest`, `UiFormatTest` в `mobile-fit-baddy/app/src/test/`.


## Критерии готовности
- [x] `./gradlew testDebugUnitTest` и lint зелёные

## Зависимости
- [AND-02](AND-02.md) — [Android] Splash, вход, регистрация, профиль

## Вопросы
Нет открытых вопросов.
