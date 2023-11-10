Проект «API для Yatube»
=====


Описание проекта
----------
Разработан API для проекта социальной сети. Реализована возможность добавления, 
удаления и изменения постов и комментариев. Настроена пагинация, пермишены.

# Инструкция для развёртывания проекта:
### Клонировать репозиторий и перейти в него в командной строке:
`git clone git@github.com:TDVwork696/api_final_yatube.git`\
`cd api_final_yatube`

### Cоздать и активировать виртуальное окружение:
`python -m venv venv`\
`source venv/bin/activate`

### Установить зависимости из файла requirements.txt:
`python -m pip install --upgrade pip`\
`pip install -r requirements.txt`

### Выполнить миграции:
`python manage.py migrate`

### Запустить проект:
`python manage.py runserver`

# Примеры запросов:
## - Получение публикаций:
### http://127.0.0.1:8000/api/v1/posts/

## - Создание публикации:
### http://127.0.0.1:8000/api/v1/posts/

## - Получение публикации:
### http://127.0.0.1:8000/api/v1/posts/{id}/

## - Обновление публикации:
### http://127.0.0.1:8000/api/v1/posts/{id}/

## - Частичное обновление публикации
### http://127.0.0.1:8000/api/v1/posts/{id}/

## - Удаление публикации
### http://127.0.0.1:8000/api/v1/posts/{id}/

## - Получение комментариев
### http://127.0.0.1:8000/api/v1/posts/{post_id}/comments/

## - Добавление комментария
### http://127.0.0.1:8000/api/v1/posts/{post_id}/comments/

## - Получение комментария
### http://127.0.0.1:8000/api/v1/posts/{post_id}/comments/{id}/

## - Обновление комментария
### http://127.0.0.1:8000/api/v1/posts/{post_id}/comments/{id}/

## - Частичное обновление комментария
### http://127.0.0.1:8000/api/v1/posts/{post_id}/comments/{id}/

## - Удаление комментария
### http://127.0.0.1:8000/api/v1/posts/{post_id}/comments/{id}/

## - Список сообществ
### http://127.0.0.1:8000/api/v1/groups/

## - Информация о сообществе
### http://127.0.0.1:8000/api/v1/groups/{id}/

## - Подписки
### http://127.0.0.1:8000/api/v1/follow/

## - Подписка
### http://127.0.0.1:8000/api/v1/follow/

## - Получить JWT-токен
### http://127.0.0.1:8000/api/v1/jwt/create/

## - Обновить JWT-токен
### http://127.0.0.1:8000/api/v1/jwt/refresh/

## - Проверить JWT-токен
### http://127.0.0.1:8000/api/v1/jwt/verify/

# Использованные технологии:
## - Язык програмирования - Python
## - Фреймворк Django 
## - API 

# Об авторе:
## https://github.com/TDVwork696