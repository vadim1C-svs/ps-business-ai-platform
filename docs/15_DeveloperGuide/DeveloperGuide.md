# Developer Guide

## Локальный запуск

```bash
docker compose up -d
```

## Backend

```bash
cd backend
python -m venv .venv
pip install -r requirements.txt
uvicorn app.main:app --reload
```

## 1С

Создать расширение, подсистему `ps_BusinessAI`, регистры и общие модули.
