# Threat Model

## Угрозы и меры

### Несанкционированный доступ к Telegram
- привязка ChatID;
- роли;
- отключение пользователя;
- audit log.

### Подмена запроса от 1С
- HMAC signature;
- timestamp;
- nonce;
- HTTPS.

### Replay attack
- проверка nonce;
- TTL nonce;
- отклонение старых timestamp.

### Ошибка AI
- AI не имеет прямого SQL;
- только tool calling;
- проверка прав перед tool;
- read-only в MVP.
