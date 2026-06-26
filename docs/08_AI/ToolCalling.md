# Tool Calling

## Примеры tools

- `metrics.get_balance`;
- `metrics.get_sales`;
- `metrics.get_debts`;
- `metrics.get_top_products`;
- `metrics.get_stock_problems`;
- `reports.get_daily_report`.

## Правила

1. Tool имеет описание.
2. Tool проверяет права.
3. Tool работает только с агрегированными данными.
4. Tool логирует вызов.
5. AI не выполняет SQL напрямую.
