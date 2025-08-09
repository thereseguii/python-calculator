#  🧮 MathOps: Flask Scientific Calculator

This is a **Flask**-based scientific calculator web app, built using **Python** and **SQLAlchemy** for database management. The app allows users to perform mathematical operations like addition, subtraction, multiplication, division, and even advanced functions such as square roots and trigonometric functions.

The calculator's history is saved in a **PostgreSQL** database, which persists between sessions.

## 🌐 Live Demo

You can access the live version of the app here:

[**Flask Scientific Calculator**](https://calculator-kfcm.onrender.com)

## 🛠️ Features

- Basic arithmetic operations ➗ (+, -, *, ÷)
- Scientific functions 🧑‍🔬 (sqrt, sin, cos, tan, log)
- History of calculations (stored in a **PostgreSQL** database)
- Responsive and user-friendly interface 💻

## 📥 Installation

To run this app locally, follow these steps:

### 1. Clone the repository:
   ```
   git clone https://github.com/thereseguii/calculator.git
   cd calculator
  ```
### 2. Create a virtual environment:
  ```
  python3 -m venv venv
  ```
### 3. Activate the virtual environment:
  On Windows:
  ```
  venv\Scripts\activate
  ```
  On macOS/Linux:
  ```
  source venv/bin/activate
  ```
### 4. Install the required dependencies:
  ```
  pip install -r requirements.txt
  ```
### 5. Set up your local database (SQLite by default):
  ```
  python app.py
  ```

### Visit the app in your browser at http://127.0.0.1:5000/ 🚀.

## 🌍 Deployment

This app is deployed on **Render** and can be accessed at the following link:

Flask Scientific Calculator on Render

To deploy the app on Render:

Go to Render.com and create a new web service.

Link your GitHub repository (thereseguii/calculator).

Set the Start Command to:
```
gunicorn app:app
```
Add the PostgreSQL database to your service and configure the DATABASE_URL in Render's environment variables.

## 🖥️ Technologies Used
- Python 3

- Flask

- Flask-SQLAlchemy (for database management)

- Gunicorn (for production deployment)

- PostgreSQL (for persistent history)

- HTML/CSS/JS (for the front end)

## 🧑‍💻 Author
Therese Segui 
🔗 github.com/thereseguii 
📧 therese.serranosegui@gmail.com

