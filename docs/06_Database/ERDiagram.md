# ER Diagram

```mermaid
erDiagram
    CLIENTS ||--o{ DATABASES : owns
    CLIENTS ||--o{ LICENSES : has
    CLIENTS ||--o{ TELEGRAM_USERS : has
    DATABASES ||--o{ METRICS : sends
    CLIENTS ||--o{ AUDIT_LOG : writes
```
