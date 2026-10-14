---
id: AND-01
title: "[Android] Каркас приложения: Retrofit, сессия, навигация"
assignee: Soloveve
labels: [module:android, type:feature, sprint-1]
milestone: "Sprint 1"
status: done
story_points: 5
related_us: [US-A1]
---
## Что сделать
Gradle-проект, клиент API, хранение токена.

## Детали / спецификация
- `mobile-fit-baddy/` (SDK 34, min 26, Java 17), `mobile-fit-baddy/app/src/main/java/com/fitquest/app/api/` (Retrofit, `AuthInterceptor`, DTO), `auth/SessionStore.java` (EncryptedSharedPreferences), `ui/MainActivity.java` (Den/Quest/Trail/Calls/Pack).


## Критерии готовности
- [x] `./gradlew testDebugUnitTest` и lint зелёные

## Зависимости
Нет.

## Вопросы
Нет открытых вопросов.
