# FORTIS – бэкенд для сбора заявок

Сервер (Node.js + Express) принимает заявки, валидирует, сохраняет в MongoDB, возвращает ID.  
Демо-портфолио.

---

## 🔗 Ссылки

| Что | Ссылка |
|-----|--------|
| Демо-сайт (виджет API) | [тык](https://dastfantast4-sys.github.io/fortis-dev/) |
| Базовый URL бэкенда | [тык](https://fortis-dev.onrender.com) |
| `/ping` – проверка | [тык](https://fortis-dev.onrender.com/ping) |
| Swagger-документация | [тык](https://fortis-dev.onrender.com/api-docs) |
| Код бэкенда | [тык](https://github.com/dastfantast4-sys/fortis-dev/tree/main/backend) |

---

## ⚙️ Возможности

- Приём заявок (имя, email, тариф, сообщение)
- Валидация (Joi)
- Сохранение в MongoDB Atlas
- Возврат ID заявки
- Эндпоинт `/ping`
- Swagger-документация

---

## 🧪 Проверка

1. **Пинг** → [fortis-dev.onrender.com/ping](https://fortis-dev.onrender.com/ping) – ответ `{"status":"ok"}`
2. **Виджет** → на [демо-сайте](https://dastfantast4-sys.github.io/fortis-dev/) в правом нижнем углу, нажмите «Отправить».
3. **Swagger** → [fortis-dev.onrender.com/api-docs](https://fortis-dev.onrender.com/api-docs) – все методы.

---

## 📊 Технологии

| Компонент | Технология |
|-----------|------------|
| Сервер | Node.js + Express |
| БД | MongoDB (Mongoose) |
| Аутентификация | JWT, bcrypt |
| Валидация | Joi |
| Документация | Swagger |
| Хостинг | Render |

---

## 📁 Структура
backend/
├── .env.example
├── package.json
└── src/
├── app.js
├── server.js
├── config/db.js
├── models/
├── controllers/
├── routes/
├── middleware/
└── utils/

---

## 🎯 Навыки

REST API, MongoDB, JWT, валидация, деплой, документация.

---

## 📬 Контакты

- GitHub: [@dastfantast4-sys](https://github.com/dastfantast4-sys)
- Telegram: [@ваш_ник]
- Email: ваша@почта.ру

Лицензия: MIT.
