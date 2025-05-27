# Метрики (Metrics)

В проекте реализован REST-контроллер `/api/metrics`, содержащий:

- `GET /api/metrics/ping` — проверка соединения. Ответ: `"pong"`
- `GET /api/metrics/health` — статус приложения. Ответ: `"UP"`
- `GET /api/metrics` — JSON с основными метриками:
```json
{
  "total_movies": 12,
  "total_bookings": 35,
  "available_seats": 80
}
