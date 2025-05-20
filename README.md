# KazakhStyle 🛍️🇰🇿

**KazakhStyle** — это веб-приложение интернет-магазина, вдохновлённого казахской культурой. Пользователи могут регистрироваться, просматривать товары, добавлять их в корзину и оформлять заказы. Проект разработан с использованием **Django**.

---

## 🌟 Основные функции

- ✅ Регистрация и вход пользователей
- ✅ Просмотр каталога товаров
- ✅ Поиск по товарам
- ✅ Добавление товаров в корзину
- ✅ Панель администратора (Django Admin)
- ✅ Современный дизайн с адаптацией под разные устройства

---

## 🧑‍💻 Используемые технологии

| Компонент | Технология     |
|----------|----------------|
| Backend  | Django (Python) |
| Frontend | HTML, CSS (Bootstrap) |
| Auth     | Django built-in auth |
| БД       | SQLite / PostgreSQL |
| Hosting  | Fly.io / Heroku / PythonAnywhere (по выбору) |

---

## 📸 Интерфейс

### 🏠 Главная страница
![Главная страница](https://github.com/user-attachments/assets/7e0566e2-a57e-4c64-a73b-5a36a4d960dd)

### 📝 Регистрация
![Страница регистрации](https://github.com/user-attachments/assets/7322edf7-9a61-4998-8229-e5e214989752)


### 🛒 Корзина
![Корзина](https://github.com/user-attachments/assets/bec51a82-3698-4fdb-a35f-9cf0d4fa5e3f)

---

## ⚙️ Установка и запуск локально

```bash
# Клонировать репозиторий
git clone https://github.com/your-username/kazakhstyle.git
cd kazakhstyle

# Создать виртуальное окружение
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Установить зависимости
pip install -r requirements.txt

# Применить миграции
python manage.py migrate

# Запустить сервер
python manage.py runserver
