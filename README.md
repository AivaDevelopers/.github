# Aiva Dating

Добро пожаловать в организацию **Aiva Dating** на GitHub Enterprise.

> Цель — развивать платформу знакомств с умным алгоритмом подбора и современным UI.

---

## Основные репозитории

| Repo | Описание |
|------|----------|
| **backend-api**    | REST / WebSocket API, бизнес‑логика |
| **frontend-web**   | PWA‑клиент на React |
| **sql-algorithm**  | Схема Postgres + функции совместимости |
| **infra-terraform**| IaC: облако, базы, S3 |
| **infra-helm**     | Helm‑чарты сервисов |
| **docs**           | ТЗ, схемы, ADR |

*(список автоматически пополняется по мере роста проекта)*

---

## Git‑flow

* `main` — прод, защищён (PR + 2 review, status checks).  
* `develop` — интеграционная ветка.  
* `feature/<issue>` — задачи, удаляются после merge.

---

## Команда

| Роль        | GitHub ID |
|-------------|-----------|
| Backend dev | @backend‑login |
| Frontend dev| @frontend‑login |

---

## Быстрый старт

```bash
git clone git@github.com:aiva-dating/backend-api.git
cd backend-api
./gradlew bootRun
```

---

© 2025 Aiva Inc.
