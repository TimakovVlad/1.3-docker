## Задание 2
Выполняем команду для сборки образа:
```bash
docker build -t my-django-app .
```
Выполняем команду для запуска контейнера:
```bash
docker run -d -p 8000:8000 --env-file .env my-django-app
```
Это запустит Django-сервер и сделает его доступным по адресу http://localhost:8000.