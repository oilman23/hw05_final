# Yatube
Финальный проект по Django курса ЯндексПрактикум - Yatube.
Данный проект был выполнен весной 2021 года, спустя 3 месяца изучения python.

### Описание проекта
Проект создан для общения и коммуникации между людьми (аналог twitter). На сайте предусмотрена система регистрации пользователей, в любой момент авторизованный пользователь может изменить свой пароль.
Авторизованный пользователь может создать новую группу, написать новый пост с возможностью привязки к группе, удалять и редактировать свои записи, добавить коментарий к существующему посту, подписаться на другого пользователя.
На главной странице доступны все записи сообщества, также можно сделать фильтрацию по избранным авторам. У каждого пользователя есть своя страница, на которой можно посмотреть все его посты, а также увидеть статистику по количеству постов, подписчиков и подписок.

### Технологии
- Django framework

### Запуск проекта в dev-режиме
- выполнить команду ```python -m venv venv```
- выполнить команду ```source venv/Scripts/activate```
- выполнить команду ```pip install -r requirements.txt```
- зайти в директорию yatube
- выполнить команду ```python manage.py makemigrations```
- выполнить команду ```python manage.py migrate```
- выполнить команду ```python manage.py runserver```

проект будет доступен по адресу http://127.0.0.1:8000/

### Автор
Владислав Татаринов