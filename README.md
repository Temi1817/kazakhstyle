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
![Главная страница](![image](https://github.com/user-attachments/assets/6263cfc7-a5bd-47ba-9c99-ec2ab754dcb0)
)

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
