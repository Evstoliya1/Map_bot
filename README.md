# Картографический бот Telegram

Этот проект представляет из себя Telegram бота, который взаимодействует с пользователями, позволяя отображать города на карте и управлять списком городов пользователя.

## Основные возможности

- **Отображение городов на карте**: Бот может отображать выбранные города на карте с помощью Cartopy и Matplotlib.
- **Сохранение городов**: Пользователи могут сохранять интересующие их города в свой персональный список.
- **Просмотр сохраненных городов**: Бот предоставляет список всех сохраненных пользователем городов.

## Технологии

- **Python 3**: Язык программирования.
- **SQLite**: База данных для хранения информации о пользователях и городах.
- **Matplotlib и Cartopy**: Библиотеки для создания графического представления данных.
- **Telebot**: Библиотека для создания и управления Telegram ботами.

## Установка и запуск

1. **Клонируйте репозиторий:**
```bash
git clone <url_to_repository>
cd <repository_name>
```
2. **Установите зависимости:**
```bash
pip install -r requirements.txt
```
3. **Настройте переменные окружения:**

Откройте файл config.py в корневом каталоге проекта и укажите в нем необходимые переменные:
```bash
TOKEN=<your_telegram_bot_token>
```
4. **Запуск бота:**
```bash
python bot.py
```

## Использование

- `/start` - начать работу с ботом и получить приветственное сообщение.
- `/help` - получить список доступных команд.
- `/show_city <city_name>` - отобразить указанный город на карте.
- `/remember_city <city_name>` - сохранить город в список избранных.
- `/show_my_cities` - показать все сохраненные города.
