# api_final_yatube 

![example workflow](https://github.com/tanya8621/api_yamdb/actions/workflows/yamdb_workflow.yml/badge.svg)
 
Server_IP: 158.160.4.58

## Описание 

 

Это API сервиса YaMDB, собирающего отзывы пользователей на различные произведения. Поддерживает регистрацию пользователей, создание записей произведений, их категорий, жанров. Возможно оставление пользователями отзывов к произведениям с выставлением оценки от 1 до 10 и комментариев к отзывам.

 

## Стек технологий 

 

Проект использует django 3.2, djangorestframework 3.12.4, django-filter. Аутентификация посредством JWT-токенов с использованием PyJWT. 

 

## Как запустить проект: 

 

Клонировать репозиторий и перейти в него в командной строке: 

 

``` 

git clone git@github.com:Arhonist/api_yamdb.git

``` 

 

``` 

cd api_yamdb

``` 

 

Cоздать и активировать виртуальное окружение: 

 

``` 

python -m venv env 

``` 

Для Windows:

``` 

source venv/Scripts/activate 

``` 

Для Linux:

``` 

source env/bin/activate

``` 

Установить зависимости из файла requirements.txt: 

 

``` 

python -m pip install --upgrade pip 

``` 

 

``` 

pip install -r requirements.txt 

``` 

 

Выполнить миграции: 

 

``` 

python manage.py migrate 

``` 

 

Запустить проект: 

 

``` 

python manage.py runserver 

``` 

 

## Документация 

 

Документация проекта сгенерирована с помощью ReDoc и доступна после запуска проекта по эндпоинту http://127.0.0.1:8000/redoc/



## Credits

Над проектом работали:
- Аушев Никита - https://github.com/Arhonist - отзывы, рейтинги, комментарии, фильтрация, поиск, вьюсеты (тимлид команды);
- Голиков Александр - https://github.com/TheUncannyMrBean - система регистрации, авторизации, пользователи, пермишны;
- Николаева Татьяна - https://github.com/tanyanikolaeva21 - категории, жанры, тайтлы.