#Проект "Kittygram"

![build passing](https://img.shields.io/badge/build-passing-brightgreen)

Проект Kittygram представляет собой веб-приложение для обмена фотографиями котиков.

## Настройка проекта

### Требования

- Python 3.8 или выше
- Docker и Docker Compose

### Установка зависимостей

```bash
pip install -r backend/requirements.txt

### Переменные окружения

```bash
Создайте файл .env в корне проекта и укажите в нем необходимые переменные окружения, такие как SECRET_KEY, DATABASE_URL и другие.

### Запуск проекта в контейнерах

```bash
docker-compose up
```
После выполнения этих шагов, проект Kittygram будет доступен по адресу http://localhost:8000/.

### Тестирование
```bash
pip install -r requirements.txt
pytest
```
### GitHub Actions

GitHub Actions настроены для автоматического тестирования и деплоя проекта Kittygram после каждого push в ветку main.
