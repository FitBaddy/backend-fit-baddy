---
id: AND-02
title: "[Android] Splash, вход, регистрация, профиль"
assignee: Soloveve
labels: [module:android, type:feature, sprint-2]
milestone: "Sprint 2"
status: done
story_points: 3
related_us: [US-A1, US-A2]
---
## Что сделать
Экраны аккаунта.

## Детали / спецификация
- `mobile-fit-baddy/app/src/main/java/com/fitquest/app/ui/SplashActivity.java` (автовход по токену), `AuthActivity.java`, `ui/profile/ProfileFragment.java` (профиль, выход, адрес API).
- Валидация формы — `auth/AuthValidator.java` (+ `AuthValidatorTest`).


## Критерии готовности
- [x] `./gradlew testDebugUnitTest` и lint зелёные

## Зависимости
- [AND-01](AND-01.md) — [Android] Каркас приложения: Retrofit, сессия, навигация

## Вопросы
Нет открытых вопросов.
