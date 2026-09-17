# 1. PostgreSQL + Adminer

## Структура проекта

```text
postgres-adminer/
├── Dockerfile
├── docker-compose.yml
└── init.sql
```
![Скрин](2026-09-17_10-26-22.png)
![Скрин](2026-09-17_10-26-28.png)
![Скрин](2026-09-17_10-26-33.png)

## Запуск

Перейти в директорию проекта:

```bash
cd postgres-adminer
```

Запустить контейнеры:

```bash
docker compose up --build
```

После запуска Adminer будет доступен по адресу:

```text
http://localhost:8080
```

![Скрин](2026-09-17_10-25-09.png)

## Данные для подключения

В Adminer необходимо указать:

| Параметр | Значение   |
| -------- | ---------- |
| System   | PostgreSQL |
| Server   | postgres   |
| Username | admin      |
| Password | admin123   |
| Database | appdb      |

---

![Скрин](2026-09-17_10-28-45.png)
