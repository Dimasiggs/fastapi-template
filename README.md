# Шаблон для fastapi проектов

Структура проекта
```
fastapi-project
├── alembic/
├── src
│   ├── auth
│   │   ├── router.py
│   │   ├── schemas.py
│   │   ├── models.py
│   │   ├── dependencies.py
│   │   ├── config.py
│   │   ├── constants.py
│   │   ├── exceptions.py
│   │   ├── service.py
│   │   └── utils.py
│   ├── users
│   │   ├── router.py
│   │   ├── schemas.py
│   │   ├── models.py
│   │   ├── dependencies.py
│   │   ├── constants.py
│   │   ├── exceptions.py
│   │   ├── service.py
│   │   └── utils.py
│   ├── config.py  # глобальный конфиг
│   ├── exceptions.py  # глобальные ошибки
│   ├── database.py  # подключение к бд и тп
│   ├── Dockerfile
│   └── main.py
├── tests/
│   ├── auth
│   └── users
├── templates/
│   └── index.html
├── requirements.txt
├── .env
├── .gitignore
├── .dockergitignore
├── .docker-compose.xml
└── alembic.ini
```