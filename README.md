# 🤖 AI Customer Service - Top Up Game

![CI/CD Pipeline](https://github.com/USERNAME_LO/ai-cs-topup-game/actions/workflows/ci-cd.yml/badge.svg)

AI Customer Service chatbot untuk layanan top up game.

## Tech Stack
- **Python** + **FastAPI**
- **Docker**
- **GitHub Actions** (CI/CD)

## Pipeline Stages
| Stage | Deskripsi |
|-------|-----------|
| 🧪 Testing | Unit test otomatis |
| 🔒 Security | Scan kerentanan kode (Bandit) |
| 🚀 Staging | Deploy otomatis |
| 🧑‍💼 UAT | Deploy dengan manual approval |
| 🏁 Production | Deploy final |

## Cara Jalankan Lokal
```bash
pip install -r requirements.txt
uvicorn app.main:app --reload
```
