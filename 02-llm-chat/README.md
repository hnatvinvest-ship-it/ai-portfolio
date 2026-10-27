# 02 · LLM Chat

Чат із великою мовною моделлю: повідомлення користувача, відповідь потоком (SSE) і обробка таймаутів та помилок API.

## Скріншот

_Буде додано, коли інтерфейс буде готовий._

## Запуск

```bash
cd 02-llm-chat
cp .env.example .env   # вказати свій LLM_API_KEY
python3 -m venv .venv && source .venv/bin/activate
pip install -e ".[dev]"
uvicorn app.main:app --reload
```

Ключ API зберігається лише у `.env`, який не потрапляє в репозиторій.

_Проєкт у розробці._
