# API Yatube

**Yatube** - это блог, в котором пользователи могут публиковать свои записи и фото.

**API Yatube** поддерживает обмен данными в формате *JSON*.

Система аутентификация реализована через получение JWT-токена. Функционал API предоставляет следующие ресурсы:

- Записи
- Комментарии
- Группы

Реализована возможность подписываться на других пользователей.

Развернув проект у себя, Вы можете ознакомиться с документацией к API по ссылке [http://localhost:8000/redoc/](http://localhost:8000/redoc/).

* Python 3
* Django Rest Framework
* [Simple JWT](https://django-rest-framework-simplejwt.readthedocs.io/en/latest/#simple-jwt)
* SQLite

## Запуск проекта ##
### 1. Склонировать репозиторий

### 2. Создать виртуальное окружение и активировать его
```
python -m venv venv
source venv/Scripts/activate
```
### 3. Установить необходимые пакеты
```
pip install -r requirements.txt
```
### 4. Выполнить миграции
Из папки */API_Yatube/yatube_api*, выполнить команду
```
python manage.py migrate
```
### 5. Запустить проект
```
python manage.py runserver
```
### Готово! 
