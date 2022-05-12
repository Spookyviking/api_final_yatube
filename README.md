# api_yatube
Это проект API для Yatube.

## Технологии
- [Python 3.7.0](https://www.python.org/downloads/release/python-388/)
- [Django 2.2.16](https://www.djangoproject.com/)
- [Django Rest Framework 3.12.4](https://www.django-rest-framework.org/)

## Как запустить проект:
###### Клонировать репозиторий и перейти в его файл проекта:
```
git clone https://github.com/EscapeFromHell/api_final_yatube.git
```
```
cd api_final_yatube
```
###### Cоздать и активировать виртуальное окружение:
```
python -m venv venv
```
```
source venv/Scripts/activate
```
###### Установить зависимости из файла requirements.txt:
```
python -m pip install --upgrade pip
```
```
pip install -r requirements.txt
```
###### Выполнить миграции:
```
python manage.py migrate
```
###### Запустить проект:
```
python manage.py runserver
```
# Примеры. Некоторые примеры запросов к API.

## Получение публикаций
```
http://127.0.0.1:8000/api/v1/posts/
```
## Создание публикации
```
http://127.0.0.1:8000/api/v1/posts/
```
## Получение комментариев
```
http://127.0.0.1:8000/api/v1/posts/{post_id}/comments/
```
## Добавление комментария
```
http://127.0.0.1:8000/api/v1/posts/{post_id}/comments/
```
## Получение списка доступных сообществ.
```
http://127.0.0.1:8000/api/v1/groups/
```
### Автор
Максим Остапенко

spookyvikingooth@gmail.com

https://github.com/Spookyviking
