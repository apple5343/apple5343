# Привет! 👋 Я Айнур

Backend-разработчик на Go, студент 2 курса КФУ, Казань.

---

## 🛠 Стек

![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-000?style=for-the-badge&logo=apachekafka)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-000?style=for-the-badge&logo=grpc&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

---

## 💼 Командная разработка

### 🗂 Disk — распределённое файловое хранилище — [repo](https://github.com/apple5343/disk)
Микросервисная система для хранения и организации файлов. Разработал **file-storage-service** и **file-data-service**:
- Асинхронная загрузка файлов через **MinIO** + **Kafka**
- Управление процессами через **Redis** (блокировки, отмена загрузки)
- Graceful shutdown с таймаутом 20 минут — активные загрузки не обрываются при деплое
- Rate limiting и Semaphore Weighted для защиты Kafka-консьюмеров от перегрузки

### 💬 Chat Service — микросервис онлайн-чата — [repo](https://github.com/apple5343/chat-service)
Сервис для real-time-коммуникации внутри команд. Разработал бэкенд чата и модуль соединений (Hub):
- Real-time-сообщения через **WebSocket** + **Redis Pub/Sub**
- Гарантия доставки через **Redis Streams**
- Горизонтальное масштабирование за счёт нескольких инстансов Hub
- **gRPC** для межсервисного взаимодействия, **MongoDB** для хранения истории сообщений

---

## 📂 Соло-проект

### 🚗 Auto Salon API — бэкенд-система управления автосалоном — [repo](https://github.com/apple5343/salon)
От архитектуры до продакшн-деплоя — в одиночку.
- **REST API** для управления брендами, автомобилями, клиентами, сотрудниками и продажами
- Слоистая архитектура (transport → service → repository → infrastructure) с DI-контейнером **uber-go/fx**
- **JWT-аутентификация** (access + refresh) и ролевой доступ (admin / employee)
- **Модуль аналитики** с агрегацией данных: продажи за период, состояние склада, метрики по сотрудникам и поставщикам
- Генератор реалистичных тестовых данных с настраиваемой интенсивностью событий
- **CI/CD** на GitHub Actions: тесты → сборка Docker-образов → автодеплой

**Стек:** Go (Echo), PostgreSQL, Redis, uber-go/fx, JWT, Docker, testcontainers-go, GitHub Actions

---

## 🏆 Олимпиада Т-Банк PROD 2025

Участвовал в отборочном и финальном этапах олимпиады по backend-разработке от Т-Банка.

- **Отборочный этап** — [Promo Code Backend](https://github.com/apple5343/Promo-Code-Backend): бэкенд для системы промокодов
- **Финал, индивидуальный этап** — [Ad Service](https://github.com/apple5343/ad-service): сервис управления рекламными объявлениями
- **Финал, командный этап** — приложение для поиска менторов, кросс-функциональная команда (backend + mobile). Отвечал за интеграцию backend с мобильным клиентом

---

## 🎓 Образование и курсы

| Курс | Организация | Период |
|------|-------------|--------|
| Веб-разработка на Go | Яндекс | Дек 2024 |
| Программирование на Go | Яндекс | 2023 — 2024 |
| Основы промышленного программирования | Яндекс | 2022 — 2023 |
| Основы программирования на Python | Яндекс | 2021 — 2022 |
