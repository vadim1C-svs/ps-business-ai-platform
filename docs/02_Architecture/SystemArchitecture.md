# System Architecture

## Архитектурный стиль

На первом этапе — modular monolith с возможностью выделения сервисов.

```text
Presentation Layer: Telegram Bot, Web UI, Admin UI
Application Layer: Use Cases, Commands, Queries
Domain Layer: Client, Database, License, Metrics, User, Notification, AI Tool
Infrastructure Layer: PostgreSQL, Redis, Telegram API, 1C HTTP API, AI Providers
```

## Главный принцип

1С не открывается напрямую наружу. Расширение 1С само инициирует исходящие HTTPS-запросы на backend.

## Компоненты

- 1C Extension Agent;
- Backend API;
- Telegram Bot;
- Admin Panel;
- Metrics Storage;
- Notification Service;
- AI Gateway;
- License Service;
- Audit Service.
