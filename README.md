# Telegram Бот для Ссылок

## Описание

Это Telegram бот, созданный с использованием NestJS, который помогает пользователям управлять и делиться ссылками в чатах Telegram.

## Настройка проекта

1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/yolojewjitsu/telegram-link-bot.git
   ```

2. Установите зависимости:
   ```bash
   cd telegram-link-bot
   npm install
   ```

3. Создайте файл `.env` в корневой директории проекта со следующими переменными окружения:
   ```bash
   DB_HOST=ваш_хост_базы_данных
   DB_PORT=ваш_порт_базы_данных
   DB_USERNAME=ваше_имя_пользователя_базы_данных
   DB_PASSWORD=ваш_пароль_базы_данных
   DB_NAME=ваше_имя_базы_данных
   TELEGRAM_TOKEN=ваш_токен_telegram_бота
   ```

4. Запустите приложение:
   ```bash
   npm run start
   ```

## Использование

1. Запустите бота и отправьте ему ссылку, чтобы добавить ее в базу данных.
2. Используйте команду `/list`, чтобы просмотреть список ссылок в базе данных.
3. Используйте команду `/share`, чтобы поделиться ссылкой в чате.

      