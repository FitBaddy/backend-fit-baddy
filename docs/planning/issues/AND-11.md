---
id: AND-11
title: "[Android] Обновление токена при 401"
assignee: Soloveve
labels: [module:android, type:feature, sprint-6]
milestone: "Sprint 6"
status: todo
story_points: 2
related_us: [US-A1]
---
## Что сделать
Повтор запроса после `POST /auth/refresh`.

## Детали / спецификация
- `mobile-fit-baddy/app/src/main/java/com/fitquest/app/api/AuthInterceptor.java` → OkHttp `Authenticator`; хранить refresh-токен в `SessionStore`.


## Критерии готовности
- [ ] `./gradlew testDebugUnitTest` и lint зелёные

## Зависимости
- [AND-02](AND-02.md) — [Android] Splash, вход, регистрация, профиль

## Вопросы
Нет открытых вопросов.
