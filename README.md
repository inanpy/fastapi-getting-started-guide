# 🚀 FastAPI - Getting Started Guide

This is a simple, beginner-friendly FastAPI project based on the Medium article:
**“Getting Started with FastAPI: A Step-by-Step Beginner’s Guide”**

📖 Read the full article: [Getting Started with FastAPI: A Step-by-Step Beginner’s Guide](https://medium.com/@inandelibas/getting-started-with-fastapi-a-step-by-step-beginners-guide-c2c5b35014e9)

## 💡 Features Covered

- FastAPI installation and setup
- First route example with `@app.get("/")`
- Path & Query Parameters
- Request Body with Pydantic Models
- Response handling & status codes
- Async endpoints & concurrency
- Automatic API docs with Swagger UI
- Project structure for growing apps
- Router usage with `include_router()`

## ▶️ How to Run

```bash
git clone https://github.com/inanpy/fastapi-getting-started-guide.git
cd fastapi-getting-started-guide
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
uvicorn app.main:app --reload
```

Visit:
- Swagger UI: http://127.0.0.1:8000/docs
- ReDoc: http://127.0.0.1:8000/redoc

## 📂 Project Structure

See `app/` folder for full implementation.

## 👏 Like it?

Feel free to ⭐️ star the repo and clap the article if you found it useful!
