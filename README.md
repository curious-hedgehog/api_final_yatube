### Описание проекта
**API для YaTube** - платформы для блогов с возможностью регистрироваться, добавлять и комментировать посты, а также подписываться на других пользователей.

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/BadChemist/api_final_yatube
```

```
cd kittygram
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```

Документация API:
```http://127.0.0.1:8000/redoc/```

### Примеры использования API

Получить список публикаций:
```GET http://127.0.0.1:8000/api/v1/posts/```

Получить JWT-токен:
```GET http://127.0.0.1:8000/api/v1/jwt/create/```

Создать публикацию:
```POST http://127.0.0.1:8000/api/v1/posts/```
