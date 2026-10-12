# 🎓 Scholyx — Scholarship Information and Eligibility Checker

A web-based platform designed to help students discover scholarship opportunities and check their eligibility based on academic performance, family income, category, course, and other scholarship requirements.

## 📌 About the Project

Finding suitable scholarships can be challenging because eligibility criteria vary across scholarship providers. Scholyx aims to provide a centralized platform where students can explore scholarship opportunities, understand eligibility requirements, and determine whether they qualify based on their profiles.

## ✨ Key Features

- 🔍 Browse and search available scholarships
- 🎯 Check scholarship eligibility based on student profiles
- 📋 View scholarship eligibility criteria
- 💰 View scholarship benefits and amounts
- 📅 Track application deadlines
- 📄 View required documents
- 🔖 Save relevant scholarships

## 🛠️ Technology Stack

### Frontend

- React.js
- Vite

### Backend

- Python
- Django
- Django REST Framework

### Database

- MySQL

### Development Tools

- Git and GitHub
- Visual Studio Code
- Postman

## 📂 Project Structure

```text
Scholyx/
├── backend/
│   ├── config/
│   ├── accounts/
│   ├── scholarships/
│   ├── eligibility/
│   ├── manage.py
│   ├── requirements.txt
│   └── .env
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── package.json
│   └── vite.config.js
├── .gitignore
└── README.md
```

## 🚀 Getting Started

### Prerequisites

Ensure the following tools are installed:

- Python
- Node.js and npm
- MySQL
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/Madhurashastry14/Scholyx.git
cd Scholyx
```

### 2. Backend Setup

Navigate to the backend directory:

```bash
cd backend
python -m venv venv
```

Activate the virtual environment.

**Windows (PowerShell):**

```powershell
.\venv\Scripts\Activate.ps1
```

Install the Python dependencies:

```bash
pip install -r requirements.txt
```

Create a `.env` file inside the `backend` directory and configure your local MySQL credentials:

```env
DB_NAME=scholyx
DB_USER=your_mysql_username
DB_PASSWORD=your_mysql_password
DB_HOST=localhost
DB_PORT=3306
```

Create the `scholyx` database in MySQL if it does not already exist.

Run the database migrations:

```bash
python manage.py migrate
```

Start the Django development server:

```bash
python manage.py runserver
```

The backend will be available at `http://127.0.0.1:8000/`.

### 3. Frontend Setup

Open a new terminal and navigate to the frontend directory from the repository root:

```bash
cd frontend
npm install
npm run dev
```

Open the local URL displayed in the terminal, usually `http://localhost:5173/`.

## 🚧 Project Status

**Currently under development.**

## 👥 Team

- Akanksha
- G Madhura Shastry
- Muralikrishna D
- Niveditha Marcopolo Totar

This project is being developed as a college mini project.

---
