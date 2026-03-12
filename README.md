# 🛍️ Flask Market Application

A fully functional **Flask web application** that simulates a marketplace where users can register, log in, and buy or sell items.  
This project demonstrates user authentication, secure password hashing, database management with SQLAlchemy, and clean form handling with Flask‑WTF.

---

## 🚀 Features

- 🧾 User registration and login with validation  
- 🔒 Encrypted password storage using **Flask‑Bcrypt**  
- 🧭 Session management via **Flask‑Login**  
- 🛒 Marketplace logic for buying and selling items  
- 📦 SQLite database with ORM models using **SQLAlchemy**  
- 🎨 Responsive UI with **Bootstrap** and Jinja2 templates  
- 🌐 Deployable on **Render**, **PythonAnywhere**, or any WSGI host  

---

## 🧠 Tech Stack

| Layer | Technology |
|-------|-------------|
| Backend | Flask (Python) |
| Database | SQLite (SQLAlchemy) |
| Authentication | Flask‑Login, Flask‑Bcrypt |
| Forms | Flask‑WTF, WTForms |
| Frontend | HTML, CSS, Jinja2 Templates |
| Deployment | Render / PythonAnywhere / Gunicorn |

---

## 📁 Project Structure



---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone [github.com](https://github.com/YOURUSERNAME/flask-market.git)
cd flask-market


## Create and activate a virtual environment
## Mac / Linux
```bash
python3 -m venv venv
source venv/bin/activate

## Windows
```bash
python -m venv venv
venv\Scripts\activate

## Install dependencies from requirements.txt
```bash
pip install -r requirements.txt

## Initialize the database
```bash
python
>>> from market import db
>>> db.create_all()
>>> exit()

## Run the application
```bash
python3 run.py

