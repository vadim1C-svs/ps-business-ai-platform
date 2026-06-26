# OpenAPI Specification Draft

Все endpoints имеют префикс `/api/v1`.

## Группы

- `/auth`;
- `/clients`;
- `/databases`;
- `/metrics`;
- `/telegram`;
- `/licenses`;
- `/admin`;
- `/ai`;
- `/health`.

## Формат ошибок

```json
{"success": false, "error": {"code": "LICENSE_EXPIRED", "message": "License expired", "details": {}}}
```
