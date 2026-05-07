# Flask Web Application Deployment using PaaS

## Project Overview

This project demonstrates how to design and deploy a web application in a PaaS (Platform as a Service) environment using Flask, GitHub, and Render.

The application is developed using Python Flask framework and deployed online using Render cloud platform.

---

## Technologies Used

- Python
- Flask
- Gunicorn
- Git
- GitHub
- Render (PaaS)

---

## Project Structure

```bash
mywebapp/
│
├── app.py
├── requirements.txt
├── Procfile
├── README.md
└── templates/
    └── index.html
```

---

## Installation Steps

### 1. Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/mywebapp.git
```

### 2. Open Project Folder

```bash
cd mywebapp
```

### 3. Create Virtual Environment

```bash
python -m venv venv
```

### 4. Activate Virtual Environment

#### Windows

```bash
.\venv\Scripts\Activate.ps1
```

#### Mac/Linux

```bash
source venv/bin/activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run Application Locally

```bash
python app.py
```

Open browser:

```bash
http://127.0.0.1:5000
```

---

## Deployment Steps

1. Push project to GitHub
2. Connect GitHub repository with Render
3. Configure:
   - Build Command:
     ```bash
     pip install -r requirements.txt
     ```
   - Start Command:
     ```bash
     gunicorn app:app
     ```
4. Deploy application

---

## Live Deployment

Application deployed using Render PaaS platform.

---

## Features

- Flask web application
- HTML frontend
- Cloud deployment
- GitHub integration
- PaaS hosting

---

## Conclusion

This project successfully demonstrates the deployment of a Flask web application using a PaaS cloud platform. The application is hosted online through Render and managed using GitHub version control.
