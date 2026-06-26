# AI Architecture

## Цель

AI-модуль должен позволить пользователю задавать вопросы естественным языком.

## Принцип безопасности

AI не получает прямой доступ к базе 1С. AI может вызывать только разрешенные tools.

```text
User Message -> Intent Recognition -> Tool Selection -> Permission Check -> Tool Execution -> Answer Generation
```
