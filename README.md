# Привет! 👋 Я Айнур

Backend-разработчик на Go, студент 1 курса КФУ в Казани. 

**Telegram**: [@ainursalahiev](https://t.me/ainursalahiev)

---

## 🛠 Стек

![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-000?style=for-the-badge&logo=apachekafka)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-000?style=for-the-badge&logo=grpc&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E00?style=for-the-badge&logo=amazon-s3&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

---

## 💼 Опыт командной разработки

### 🗂 Аналог Яндекс.Диска — [Disk](https://github.com/apple5343/disk)
Командный учебный проект. Разработал **file-storage-service** и **file-data-service**:
- Асинхронная загрузка файлов через **MinIO** + **Kafka**
- Управление процессами через **Redis** (блокировки, отмена загрузки)
- Graceful shutdown с таймаутом 20 минут
- Rate limiting и Semaphore для Kafka consumers

### 💬 Микросервис чата — [Chat Service](https://github.com/apple5343/chat-service)
Командный проект в рамках курса "Веб-разработка на Go" (Яндекс). Разработал Chat Service:
- Real-time сообщения через **WebSocket** + **Redis Pub/Sub**
- Гарантия доставки через **Redis Streams**
- Горизонтальная масштабируемость (несколько инстансов Hub)
- **gRPC** для межсервисного взаимодействия, **MongoDB** для хранения

---

## 📂 Собственные проекты

### 🚗 Auto Salon API — [salon](https://github.com/apple5343/salon)
Backend-система управления автосалоном (учебный проект 1 курса КФУ).
- **REST API** для управления брендами, автомобилями, клиентами, сотрудниками и продажами
- **Модуль аналитики** с агрегацией данных (продажи, склад, метрики эффективности)
- **Генератор реалистичных тестовых данных** на основе датасетов для демонстрации и тестирования
- **Стек:** Go (Echo), PostgreSQL, Redis, JWT-аутентификация
- **Тестирование:** Интеграционные тесты с использованием `testcontainers-go`
- **CI/CD** Настроен пайплайн в GitHub Actions для автоматического запуска тестов и деплоя приложения.

---


## 🏆 Олимпиады и соревнования
### Олимпиада Т-Банк PROD 2025
Участвовал в отборочном и финальном этапе олимпиады по backend-разработке от Т-Банка.

- **Отборочный этап** — [Promo Code Backend](https://github.com/apple5343/Promo-Code-Backend): backend для системы промокодов
- **Финальный индивидуальный этап** — [Ad Service](https://github.com/apple5343/ad-service): сервис управления рекламными объявлениями
- **Финальный командный этап** — Разработка приложения для поиска менторов в кросс-функциональной команде (Backend + Mobile). Отвечал за интеграцию с мобильным клиентом.

---

## 🎓 Образование и курсы

| Курс | Организация | Период |
|------|-------------|--------|
| Веб-разработка на Go | Яндекс | Дек 2024 |
| Программирование на Go | Яндекс | 2023 — 2024 |
| Основы промышленного программирования | Яндекс | 2022 — 2023 |
| Основы программирования на Python | Яндекс | 2021 — 2022 |
