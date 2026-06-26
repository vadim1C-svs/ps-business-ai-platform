# PSGroup Business AI Platform

Enterprise-платформа ТОО "PSGroup" для интеграции 1С, Telegram/WhatsApp, веб-интерфейсов и AI-агентов.

## Первый продукт

**ps_DirectorBot** — Telegram-бот для директора, который показывает деньги, продажи, долги, остатки, отчеты и риски бизнеса.

```text
1С клиента -> Расширение ps_BusinessAIAgent -> HTTPS -> Backend PSGroup -> Telegram/WhatsApp/Web/AI -> Пользователь
```

## Стек

- 1С:Предприятие 8.3, расширения
- Python 3.12+
- FastAPI
- PostgreSQL
- Redis
- Celery/RQ
- Docker
- Nginx
- Telegram Bot API
- AI Provider Adapter: OpenAI / Azure OpenAI / Gemini / Claude / Ollama

## Стандарт PSGroup

Все объекты 1С и внутренние компоненты используют префикс `ps_`.

```1c
// Правообладатель: ТОО "PSGroup"
```
