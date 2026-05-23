# Задание 2 — Проектирование REST API

## Пример REST API запроса

При открытии экрана партнерских магазинов мобильное приложение отправляет запрос:

```http
GET /api/v1/partner-shops
Host: api.petrushka-green.ru
Authorization: Bearer <token>
Content-Type: application/json



{
  "shops": [
    {
      "id": 1,
      "name": "Магнит",
      "description": "Сеть продуктовых магазинов",
      "imageUrl": "https://cdn.petrushka-green.ru/images/magnit.png",
      "externalUrl": "https://magnit.ru"
    },
    {
      "id": 2,
      "name": "Лента",
      "description": "Гипермаркет товаров для дома и продуктов",
      "imageUrl": "https://cdn.petrushka-green.ru/images/lenta.png",
      "externalUrl": "https://lenta.com"
    },
    {
      "id": 3,
      "name": "ВкусВилл",
      "description": "Магазин натуральных продуктов",
      "imageUrl": "https://cdn.petrushka-green.ru/images/vkusvill.png",
      "externalUrl": "https://vkusvill.ru"
    }
  ]
}
