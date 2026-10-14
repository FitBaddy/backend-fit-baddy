# Roadmap FitBaddy

Проект: **11.09.2026 — 25.12.2026**, спринты по 2 недели. Команда — 3 человека, разделение по слоям:

| Слой | Участник | Репозиторий |
|---|---|---|
| Backend (сервер-мост) | [@Hupubu](https://github.com/Hupubu) | [`backend-fit-baddy`](https://github.com/FitBaddy/backend-fit-baddy) |
| Android-приложение | [@Soloveve](https://github.com/Soloveve) | [`mobile-fit-baddy`](https://github.com/FitBaddy/mobile-fit-baddy) |
| Raspberry Pi и ИИ | [@MouseViolin](https://github.com/MouseViolin) | [`pi-fit-baddy`](https://github.com/FitBaddy/pi-fit-baddy) |

Задачи всех трёх слоёв — в `docs/planning/issues/` этого репозитория (один файл = один GitHub Issue), перенос на доску — `scripts/create_issues.sh`. Доска: <https://github.com/orgs/FitBaddy/projects/1>.

## Спринты

| № | Даты | Цель спринта |
|---|---|---|
| 1 | 11.09 – 24.09 | Каркас backend: авторизация, тренировки, питомец, телеметрия симулятора |
| 2 | 25.09 – 08.10 | Экраны Android подключены к API, живая телеметрия, ИИ на правилах |
| 3 | 09.10 – 22.10 | Тесты, CI, исправления безопасности |
| 4 | 23.10 – 05.11 | Приём телеметрии от Pi, каркас узла Pi и виртуальные датчики |
| 5 | 06.11 – 19.11 | Драйверы и алгоритм шагов, графики телеметрии, данные для ИИ |
| 6 | 20.11 – 03.12 | Пульс, API узла, модель ИИ в Colab |
| 7 | 04.12 – 17.12 | Pi end-to-end, проверка на плате |
| 8 | 18.12 – 25.12 | Сдача |

## Задачи по слоям

Сделано **68** из **138** SP.

### Нагрузка: задачи / SP по спринтам

| Участник | С1 | С2 | С3 | С4 | С5 | С6 | С7 | С8 | Всего задач / SP | Сделано / осталось SP |
|---|---|---|---|---|---|---|---|---|---|---|
| @Hupubu | 8 / 29 | 1 / 3 | 2 / 8 | 3 / 9 | 1 / 3 | 2 / 5 | — | — | 17 / 57 | 40 / 17 |
| @MouseViolin | — | 1 / 2 | — | 3 / 9 | 4 / 14 | 5 / 17 | 2 / 4 | — | 15 / 46 | 2 / 44 |
| @Soloveve | 1 / 5 | 5 / 19 | 1 / 2 | 1 / 2 | 2 / 5 | 1 / 2 | — | — | 11 / 35 | 26 / 9 |
| **Спринт, SP** | 34 | 24 | 10 | 20 | 22 | 24 | 4 | 0 | 43 / 138 | |

> Android — @Soloveve, Pi и ИИ — @MouseViolin. Pi начинается в спринте 4, поэтому у @MouseViolin почти все задачи впереди (~44 SP).

### Бэклог по приоритету (истории → задачи)

| # | История | MoSCoW | Готово задач | Задачи |
|---|---|---|---|---|
| 1 | US-A1 | Must | 5 / 6 | [BE-03](issues/BE-03.md) ✅, [BE-10](issues/BE-10.md) ✅, [AND-01](issues/AND-01.md) ✅, [AND-02](issues/AND-02.md) ✅, [AND-07](issues/AND-07.md) ✅, [AND-11](issues/AND-11.md) |
| 2 | US-B1 | Must | 2 / 2 | [BE-05](issues/BE-05.md) ✅, [AND-04](issues/AND-04.md) ✅ |
| 3 | US-C2 | Must | 2 / 2 | [BE-05](issues/BE-05.md) ✅, [AND-04](issues/AND-04.md) ✅ |
| 4 | US-D1 | Must | 2 / 2 | [BE-06](issues/BE-06.md) ✅, [AND-03](issues/AND-03.md) ✅ |
| 5 | US-E1 | Must | 2 / 2 | [BE-07](issues/BE-07.md) ✅, [AND-05](issues/AND-05.md) ✅ |
| 6 | US-H1 | Must (симулятор) | 3 / 20 | [BE-08](issues/BE-08.md) ✅, [BE-10](issues/BE-10.md) ✅, [BE-13](issues/BE-13.md), [BE-14](issues/BE-14.md), [BE-15](issues/BE-15.md), [BE-16](issues/BE-16.md), [AND-06](issues/AND-06.md) ✅, [AND-08](issues/AND-08.md), [AND-09](issues/AND-09.md), [AND-10](issues/AND-10.md), [PI-01](issues/PI-01.md), [PI-02](issues/PI-02.md), [PI-03](issues/PI-03.md), [PI-04](issues/PI-04.md), [PI-05](issues/PI-05.md), [PI-06](issues/PI-06.md), [PI-07](issues/PI-07.md), [PI-08](issues/PI-08.md), [PI-09](issues/PI-09.md), [PI-10](issues/PI-10.md) |
| 7 | US-A2 | Must | 2 / 2 | [BE-03](issues/BE-03.md) ✅, [AND-02](issues/AND-02.md) ✅ |
| 8 | US-B2 | Must | 1 / 1 | [BE-04](issues/BE-04.md) ✅ |
| 9 | US-C1 | Must | 0 / 0 | — |
| 10 | US-F2 | Must (уведомления о событиях) | 2 / 2 | [BE-07](issues/BE-07.md) ✅, [AND-05](issues/AND-05.md) ✅ |
| 11 | US-C3 | Should | 2 / 2 | [BE-05](issues/BE-05.md) ✅, [AND-04](issues/AND-04.md) ✅ |
| 12 | US-D2 | Should | 1 / 1 | [BE-06](issues/BE-06.md) ✅ |
| 13 | US-G1 | Should | 0 / 0 | — |
| 14 | US-G2 | Should | 2 / 2 | [BE-09](issues/BE-09.md) ✅, [BE-10](issues/BE-10.md) ✅ |
| 15 | US-H2 | Should | 2 / 7 | [BE-09](issues/BE-09.md) ✅, [BE-17](issues/BE-17.md), [AI-01](issues/AI-01.md) ✅, [AI-02](issues/AI-02.md), [AI-03](issues/AI-03.md), [AI-04](issues/AI-04.md), [AI-05](issues/AI-05.md) |
| 16 | US-D3 | Should | 0 / 0 | — |
| 17 | US-E2 | Should | 0 / 0 | — |
| 18 | US-B3 | Could | 0 / 0 | — |
| 19 | US-F1 | Should | 0 / 0 | — |
| 20 | Технические и документационные | — | 3 / 4 | [BE-01](issues/BE-01.md), [BE-02](issues/BE-02.md), [BE-11](issues/BE-11.md), [BE-12](issues/BE-12.md) |

### Задачи по спринтам

#### Спринт 1 · 11.09 – 24.09 · 34 SP

| ID | Задача | Исполнитель | SP | Статус |
|---|---|---|---|---|
| [BE-01](issues/BE-01.md) | [Backend] Каркас FastAPI, PostgreSQL и Docker Compose | @Hupubu | 3 | ✅ |
| [BE-02](issues/BE-02.md) | [Backend] Шина событий внутри процесса | @Hupubu | 2 | ✅ |
| [BE-03](issues/BE-03.md) | [Backend] Регистрация, вход, JWT и профиль | @Hupubu | 5 | ✅ |
| [BE-04](issues/BE-04.md) | [Backend] Расписание и событие пропуска | @Hupubu | 3 | ✅ |
| [BE-05](issues/BE-05.md) | [Backend] Программы, сессии тренировок и история | @Hupubu | 5 | ✅ |
| [BE-06](issues/BE-06.md) | [Backend] Питомец: XP, уровень, настроение по событиям | @Hupubu | 3 | ✅ |
| [BE-07](issues/BE-07.md) | [Backend] Уведомления и сводка дашборда | @Hupubu | 3 | ✅ |
| [BE-08](issues/BE-08.md) | [Backend] Устройства, телеметрия, симулятор и WebSocket | @Hupubu | 5 | ✅ |
| [AND-01](issues/AND-01.md) | [Android] Каркас приложения: Retrofit, сессия, навигация | @Soloveve | 5 | ✅ |

#### Спринт 2 · 25.09 – 08.10 · 24 SP

| ID | Задача | Исполнитель | SP | Статус |
|---|---|---|---|---|
| [BE-09](issues/BE-09.md) | [Backend] ИИ-рекомендации на правилах и mock-подписка | @Hupubu | 3 | ✅ |
| [AND-02](issues/AND-02.md) | [Android] Splash, вход, регистрация, профиль | @Soloveve | 3 | ✅ |
| [AND-03](issues/AND-03.md) | [Android] Главный экран Den с питомцем | @Soloveve | 5 | ✅ |
| [AND-04](issues/AND-04.md) | [Android] Экран Quest: программы, сессия, история | @Soloveve | 5 | ✅ |
| [AND-05](issues/AND-05.md) | [Android] Экраны Trail и Calls | @Soloveve | 3 | ✅ |
| [AND-06](issues/AND-06.md) | [Android] Live watch: WebSocket и запасной REST | @Soloveve | 3 | ✅ |
| [AI-01](issues/AI-01.md) | [ИИ] Рекомендация на правилах с дисклеймером | @MouseViolin | 2 | ✅ |

#### Спринт 3 · 09.10 – 22.10 · 10 SP

| ID | Задача | Исполнитель | SP | Статус |
|---|---|---|---|---|
| [BE-10](issues/BE-10.md) | [Backend] Исправления безопасности и валидации | @Hupubu | 5 | ✅ |
| [BE-11](issues/BE-11.md) | [Backend] Тесты на PostgreSQL и CI-job | @Hupubu | 3 | ✅ |
| [AND-07](issues/AND-07.md) | [Android] Unit-тесты и CI-job | @Soloveve | 2 | ✅ |

#### Спринт 4 · 23.10 – 05.11 · 20 SP

| ID | Задача | Исполнитель | SP | Статус |
|---|---|---|---|---|
| [BE-12](issues/BE-12.md) | [Backend] Alembic-миграции | @Hupubu | 3 | ⬜ |
| [BE-13](issues/BE-13.md) | [Backend] Приём телеметрии от Pi: POST /telemetry/ingest с X-Device-Token | @Hupubu | 3 | ⬜ |
| [BE-14](issues/BE-14.md) | [Backend] WebSocket рассылает сохранённые точки | @Hupubu | 3 | ⬜ |
| [AND-08](issues/AND-08.md) | [Android] Офлайн-кэш последней точки и статус с датой | @Soloveve | 2 | ⬜ |
| [PI-01](issues/PI-01.md) | [Pi] Каркас узла: конфиг, часы, фабрика шины и FakeSMBus | @MouseViolin | 3 | ⬜ |
| [PI-02](issues/PI-02.md) | [Pi] Виртуальный MPU6050: регистры, сон, диапазон | @MouseViolin | 3 | ⬜ |
| [PI-04](issues/PI-04.md) | [Pi] Генераторы сигналов, сценарии и проигрыватель CSV | @MouseViolin | 3 | ⬜ |

#### Спринт 5 · 06.11 – 19.11 · 22 SP

| ID | Задача | Исполнитель | SP | Статус |
|---|---|---|---|---|
| [BE-15](issues/BE-15.md) | [Backend] Агрегаты телеметрии для графиков: шаги по дням, средний пульс | @Hupubu | 3 | ⬜ |
| [AND-09](issues/AND-09.md) | [Android] Подключение узла Pi и индикация источника данных | @Soloveve | 2 | ⬜ |
| [AND-10](issues/AND-10.md) | [Android] История телеметрии за период с графиком | @Soloveve | 3 | ⬜ |
| [AI-02](issues/AI-02.md) | [ИИ] Подготовка данных истории активности для модели | @MouseViolin | 3 | ⬜ |
| [PI-03](issues/PI-03.md) | [Pi] Виртуальный MAX30102: FIFO, указатели, переполнение | @MouseViolin | 5 | ⬜ |
| [PI-05](issues/PI-05.md) | [Pi] Драйверы Mpu6050 и Max30102 + тест переносимости | @MouseViolin | 3 | ⬜ |
| [PI-06](issues/PI-06.md) | [Pi] Подсчёт шагов на потоке отсчётов | @MouseViolin | 3 | ⬜ |

#### Спринт 6 · 20.11 – 03.12 · 24 SP

| ID | Задача | Исполнитель | SP | Статус |
|---|---|---|---|---|
| [BE-16](issues/BE-16.md) | [Backend] Сквозной контракт-тест: публикатор Pi ↔ ingest | @Hupubu | 2 | ⬜ |
| [BE-17](issues/BE-17.md) | [Backend] Эндпоинт инференса модели ИИ | @Hupubu | 3 | ⬜ |
| [AND-11](issues/AND-11.md) | [Android] Обновление токена при 401 | @Soloveve | 2 | ⬜ |
| [AI-03](issues/AI-03.md) | [ИИ] Пайплайн обучения в Google Colab | @MouseViolin | 5 | ⬜ |
| [AI-04](issues/AI-04.md) | [ИИ] Интеграция модели в backend и приложение | @MouseViolin | 3 | ⬜ |
| [PI-07](issues/PI-07.md) | [Pi] Оценка пульса с отказом при слабом сигнале | @MouseViolin | 3 | ⬜ |
| [PI-08](issues/PI-08.md) | [Pi] Sampler и локальный API /device/* | @MouseViolin | 3 | ⬜ |
| [PI-09](issues/PI-09.md) | [Pi] Публикатор TelemetryDTO в backend | @MouseViolin | 3 | ⬜ |

#### Спринт 7 · 04.12 – 17.12 · 4 SP

| ID | Задача | Исполнитель | SP | Статус |
|---|---|---|---|---|
| [AI-05](issues/AI-05.md) | [ИИ] Оценка качества рекомендаций и проверка дисклеймера | @MouseViolin | 2 | ⬜ |
| [PI-10](issues/PI-10.md) | [Pi] README узла, запись CSV и проверка на реальной плате | @MouseViolin | 2 | ⬜ |
