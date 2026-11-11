# 🏥 AI Healthcare Bot System Using Python

An AI-powered healthcare chatbot web application developed using Python, Flask, and Machine Learning technologies. The system aims to provide users with an interactive platform for healthcare-related assistance through a web interface.

## 🌐 Live Demo

🚀 **Try the application here:**

👉 [https://ai-healthcare-bot-system-using-python.onrender.com](https://ai-healthcare-bot-system-using-python.onrender.com)

The application is deployed and hosted on **Render**.

## 📌 Project Overview

The **AI Healthcare Bot System** is a web-based application designed to provide healthcare-related assistance using Python and machine learning technologies.

The project combines a Flask backend with frontend web technologies to create an interactive healthcare application.

It is designed to make healthcare information and supported prediction features accessible through a simple web interface.

## ✨ Technologies Used

| Technology           | Purpose                   |
| -------------------- | ------------------------- |
| Python               | Backend programming       |
| Flask                | Web application framework |
| HTML5                | Web page structure        |
| CSS3                 | Styling and layout        |
| JavaScript           | Frontend interactivity    |
| Scikit-learn         | Machine learning          |
| NumPy                | Numerical computing       |
| Pandas               | Data processing           |
| Flask-SQLAlchemy     | Database integration      |
| Flask-Login          | User authentication       |
| SQLAlchemy           | Database management       |
| Gunicorn             | Production web server     |
| Render               | Cloud deployment          |
| PostgreSQL / Psycopg | Database connectivity     |

## 📁 Project Structure

```text
AI-HEALTHCARE-BOT-SYSTEM-USING-PYTHON/
│
├── Health-Care-Chatbot/
│   ├── app.py
│   ├── requirements.txt
│   └── Other application files
│
├── render.yaml
├── .python-version
└── README.md
```

*Note: This is a simplified structure showing the main known project and deployment files.*

## ⚙️ Installation and Setup

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/ursdevarajan11/AI-HEALTHCARE-BOT-SYSTEM-USING-PYTHON.git
```

### 2. Navigate to the Project Folder

```bash
cd AI-HEALTHCARE-BOT-SYSTEM-USING-PYTHON
```

### 3. Install Python

Python 3.11 is recommended for dependency compatibility.

Download Python:

[https://www.python.org/downloads/release/python-3119/](https://www.python.org/downloads/release/python-3119/)

### 4. Create a Virtual Environment

```bash
py -3.11 -m venv .venv
```

### 5. Activate the Virtual Environment

For Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

### 6. Upgrade pip

```bash
python -m pip install --upgrade pip
```

### 7. Install Required Dependencies

```bash
pip install -r Health-Care-Chatbot/requirements.txt
```

### 8. Run the Application

```bash
cd Health-Care-Chatbot
python app.py
```

## 🚀 Deployment on Render

This project is deployed using **Render Web Services**.

### Deployment Configuration

| Setting        | Configuration                                                       |
| -------------- | ------------------------------------------------------------------- |
| Service Type   | Web Service                                                         |
| Runtime        | Python 3                                                            |
| Python Version | 3.11.9                                                              |
| Build Command  | `pip install -r Health-Care-Chatbot/requirements.txt`               |
| Start Command  | `gunicorn --chdir Health-Care-Chatbot app:app --bind 0.0.0.0:$PORT` |

### Deployment Steps

1. Upload or push the project to GitHub.
2. Create an account on [Render](https://render.com/).
3. Select **New Web Service**.
4. Connect your GitHub repository.
5. Select the project repository.
6. Configure the build and start commands.
7. Click **Deploy**.
8. Wait for the deployment to complete.
9. Open the generated live application URL.

### Live Application

[https://ai-healthcare-bot-system-using-python.onrender.com](https://ai-healthcare-bot-system-using-python.onrender.com)

## 📦 Requirements

The project dependencies are maintained in:

`Health-Care-Chatbot/requirements.txt`

Main packages include:

- Flask
- Flask-SQLAlchemy
- Flask-Login
- SQLAlchemy
- Scikit-learn
- NumPy
- Pandas
- Pillow
- Gunicorn
- Requests
- Psycopg

## 🔮 Future Enhancements

- Improve chatbot response accuracy.
- Add more healthcare-related assistance features.
- Improve user interface and user experience.
- Enhance database management.
- Add additional machine learning capabilities.
- Improve application performance and scalability.

## ⚠️ Disclaimer

This project is developed for educational and informational purposes only.

The application is not a replacement for professional medical advice, diagnosis, or treatment. Always consult a qualified healthcare professional for medical concerns.

## 👨‍💻 Author

**Devaraja&#x20;**

GitHub: [@ursdevarajan11](https://github.com/ursdevarajan11)

Project Repository: [AI Healthcare Bot System Using Python](https://github.com/ursdevarajan11/AI-HEALTHCARE-BOT-SYSTEM-USING-PYTHON)

## ⭐ Show Your Support

If you find this project useful, please consider giving the repository a ⭐ star on GitHub!

Thank you for visiting my project! ❤️
