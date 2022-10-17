api_yatube
# CRUD для Yatube
Проектирование REST API для приложения Yatube.
Настроены сериализаторы, view-функции и классы, вьюсеты и роутеры, регулярные выражения. Настроена аутентификация по токенам.

# Технологии:
- Python 3.8
- Django 2.2.14
- djangorestframework
- Pillow
- sorl-thumbnail

## _Как запустить проект:_
Клонировать репозиторий и перейти в него в командной строке
Cоздать и активировать виртуальное окружение:

```sh
python -m venv venv
source venv/Scripts/activate 
```
Установить зависимости из файла requirements.txt и обновить pip:
```sh
python -m pip install --upgrade pip
pip install -r requirements.txt
```

Запустить сервер:
```sh

py manage.py runserver
```
