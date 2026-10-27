# 01 · FastAPI API

REST-сервіс на FastAPI з ендпоінтом `GET /health`, валідацією запитів через Pydantic і тестами pytest.

## Скріншот

_Буде додано після першого запуску (Swagger UI на `/docs`)._

## Запуск

```bash
cd 01-fastapi-api
python3 -m venv .venv && source .venv/bin/activate
pip install -e ".[dev]"
uvicorn app.main:app --reload
```

Документація API: http://localhost:8000/docs

## Тести

```bash
pytest
```

_Проєкт у розробці: код додається на етапі 1._
