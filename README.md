# Task Manager API

## Project Description
This is a simple Task Manager REST API built using FastAPI, SQLAlchemy, Pydantic, and SQLite. It allows users to create, view, update, and delete tasks.

## Technologies Used
- Python 3
- FastAPI
- SQLAlchemy
- Pydantic
- SQLite
- Uvicorn

## Project Structure

TaskManager/
│── main.py
│── database.py
│── models.py
│── schemas.py
│── crud.py
│── requirements.txt
│── task.db
│── README.md


## Installation

### 1. Clone the repository
bash
git clone <your-github-repository-link>
cd TaskManager


### 2. Create Virtual Environment
bash
python -m venv venv


### 3. Activate Virtual Environment

Windows:
bash
venv\Scripts\activate


### 4. Install Dependencies
bash
pip install -r requirements.txt


### 5. Run the Application
bash
python -m uvicorn main:app --reload


## API Documentation

Swagger UI:

http://127.0.0.1:8000/docs


## Available APIs

- GET /tasks
- POST /tasks
- PUT /tasks/{task_id}
- DELETE /tasks/{task_id}

## Author

*Arun Kumar Murugan*