# Интернет магазин на Django
# Simple Online Shop: Manage Products and Orders with Django

Это полноценный проект интернет-магазина, разработанный на Django.
В нем я использовал ***AJAX-запросы*** для динамического обновления количества товаров на странице корзины без перезагрузки страницы, а ***asyncio*** я применял для отправки сообщений в Telegram-бота асинхронно, не блокируя основной поток выполнения приложения.

# Установка
# Installation. You must do the following steps:

1. Клонируйте репозиторий
```
https://github.com/Dimon0476/StorePython.git

cd OnlineStore
```
Если вы не используете Git, то вы можете просто скачать исходный код репозитория в ZIP-архиве и распаковать его на свой компьютер.

2. Создайте виртуальное окружение и активируйте его
```
python -m venv venv
source venv/bin/activate
```
3. Установите зависимости
```
pip install -r requirements.txt
```
4. Создайте в корне проекта .env по образу .env.example

5. Запустите миграции и загрузите данные в БД
```
python manage.py migrate
python manage.py loaddata data.json
```
6. Создайте администратора магазина
```
python manage.py createsuperuser
```
7. Запустите сервер
```
python manage.py runserver
```
Откройте браузер и перейдите по адресу http://127.0.0.1:8000/admin/. Введите имя пользователя и пароль администратора, чтобы войти в панель управления магазином.
Open your browser and go to http://127.0.0.1:8000/admin/. Enter your administrator username and password to log into your store control panel.

# Готово!
# Ready! Finish!!!
Вы успешно установили магазин на Django и готовы начать его использовать!
You have successfully installed your Django store and are ready to start using it!

# Вклад в проект
# Contribution to the project
Если у вас есть предложения по улучшению или вы обнаружили баг, не стесняйтесь создать issue, отправить pull request либо написать напрямую автору. Ваш вклад приветствуется!
If you have suggestions for improvement or find a bug, feel free to create an issue, send a pull request, or write directly to the author. This will be good!

# Автор
# Author
[Dmitry Fyodorov](https://github.com/Dimon0476)
