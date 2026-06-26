# PostgreSQL Schema

## Основные таблицы

- clients;
- databases;
- licenses;
- telegram_users;
- metrics;
- audit_log.

## metrics

```sql
create table metrics (
    id uuid primary key,
    database_id uuid not null,
    metric_type text not null,
    period_start timestamptz,
    period_end timestamptz,
    payload_json jsonb not null,
    created_at timestamptz not null
);
```
