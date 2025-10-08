
# 💰 Expense Management System
![Python](https://img.shields.io/badge/Python-3.13.2-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-1.45.0-orange?logo=streamlit)
![FastAPI](https://img.shields.io/badge/FastAPI-0.115.12-blue?logo=fastapi)
![Pydantic](https://img.shields.io/badge/Pydantic-2.11.3-lightgrey?logo=pydantic)
![Uvicorn](https://img.shields.io/badge/Uvicorn-0.34.2-purple?logo=python)
![MySQL Connector](https://img.shields.io/badge/MySQL--Connector-9.3.0-blue?logo=mysql)
![Pandas](https://img.shields.io/badge/Pandas-2.2.3-lightblue?logo=pandas)
![Requests](https://img.shields.io/badge/Requests-2.32.3-red?logo=python)
![PyTest](https://img.shields.io/badge/PyTest-8.3.5-green?logo=pytest)


An interactive **Expense Tracking System** built with **Streamlit**, **FastAPI**, and **MySQL**.  
This project allows users to log, categorize, and analyze their expenses in a clean and modern web interface.

## 🏗️ System Architecture

**Components:**

### 🌐 Streamlit Frontend
- Provides a user-friendly interface for adding, updating, and viewing expenses.
- Built with **Streamlit** for quick and interactive data visualization.

### ⚡ FastAPI Backend
- Acts as a **RESTful API server** between the frontend and the database.
- Handles data validation, CRUD operations, and business logic.

### 🗄️ MySQL Database
- Stores expense records with fields like amount, category, notes, and date.
- Optimized for structured and persistent data storage.

---

## ⚙️ Features

✅ Add, edit, and delete expense entries  
✅ Categorize expenses (Food, Entertainment, Shopping, etc.)  
✅ View daily or monthly expense summaries  
✅ Data stored securely in **MySQL**  
✅ REST API for integration or future app development  

---

## 🧩 Tech Stack

| Layer    | Technology                     |
|----------|--------------------------------|
| Frontend | Streamlit                      |
| Backend  | FastAPI                        |
| Database | MySQL                          |
| Language | Python                         |
| ORM      | Pydantic                       |

---

## 🚀 Installation & Setup

## Project Structure

- **frontend/**: Contains the Streamlit application code.
- **backend/**: Contains the FastAPI backend server code.
- **tests/**: Contains the test cases for both frontend and backend.
- **requirements.txt**: Lists the required Python packages.
- **README.md**: Provides an overview and instructions for the project.


## Setup Instructions

### 1️⃣ Clone the repository

   ```bash
   git clone https://github.com/rosewelt/expense-tracking-system.git
   cd expense-management-system
   ```
### 2️⃣ Install dependencies  
   ```commandline
    pip install -r requirements.txt
   ```
### 3️⃣ Run the FastAPI serve
   ```commandline
    uvicorn server.server:app --reload
   ```
### 4️⃣ Run the Streamlit app 
   ```commandline
    streamlit run frontend/app.py
   ```

## 📊 Example Use Case

1. Open the Streamlit app.

2. Add expenses under categories like Food, Entertainment, or Shopping.

3. Add notes and dates for better tracking.

4. Data is saved via the FastAPI backend into MySQL.
