# ✅ Asynchronous Todo REST API & Web UI (FastAPI)

![FastAPI](https://img.shields.io/badge/FastAPI-0.100+-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JWT Auth](https://img.shields.io/badge/Security-JWT_OAuth2-red?style=for-the-badge)
![SQLAlchemy](https://img.shields.io/badge/Database-SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

A lightweight, asynchronous Todo application featuring a secure REST API backend built with **FastAPI**, **SQLAlchemy**, and **JWT Authentication**, alongside an interactive web interface.

---

## 🌟 Key Features

- **⚡ Lightweight & Fast**: Asynchronous task creation, completion status toggling, and task prioritization.
- **🔐 JWT Security (`security.py`)**: Protected user endpoints, user registration, and OAuth2 bearer tokens.
- **🛡 Pydantic Validation (`schemas.py`)**: Strict request body validation and response schemas.
- **🌐 Interactive Web Interface (`index.html`)**: Built-in frontend UI for direct task interaction.

---

## ⚙️ How to Run

1. **Clone & Install:**
   ```bash
   git clone https://github.com/Juravoyev/todo_fastapi.git
   cd todo_fastapi

   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```

2. **Start FastAPI Application:**
   ```bash
   uvicorn main:app --reload
   ```

3. **API Documentation:**
   Open `http://127.0.0.1:8000/docs` in your browser.

---

## 👨‍💻 Author

**Shams Juravoyev**  
- Telegram: [@Juravoyev](https://t.me/Juravoyev)  
- LinkedIn: [Shams Juravoyev](https://www.linkedin.com/in/shams-juravoyev-3017473ab/)  
- GitHub: [@Juravoyev](https://github.com/Juravoyev)  
