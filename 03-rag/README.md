# 03 · RAG

Пошук по завантажених документах (PDF, markdown): фрагменти зберігаються в PostgreSQL з pgvector, відповідь формується лише за джерелами, і до неї додаються цитати.

## Скріншот

_Буде додано, коли буде готовий інтерфейс чату з панеллю джерел._

## Запуск

```bash
cd 03-rag
docker compose up -d        # PostgreSQL + pgvector
cp .env.example .env        # вказати LLM_API_KEY
python3 -m venv .venv && source .venv/bin/activate
pip install -e ".[dev]"
uvicorn app.main:app --reload
```

_Проєкт у розробці._
