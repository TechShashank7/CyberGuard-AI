# CyberGuard AI

A modern, interactive cybersecurity awareness platform that helps users recognize phishing scams, understand manipulation tactics, and build stronger digital safety habits through simulation and AI-assisted analysis.

![CyberGuard AI](https://img.shields.io/badge/Flask-3.x-000000?logo=flask&logoColor=white)
![CyberGuard AI](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![CyberGuard AI](https://img.shields.io/badge/Scikit-Learn-1.x-F7931E?logo=scikit-learn&logoColor=white)

## ✨ Overview

Live Demo: https://cipher-shield-p9qq.onrender.com/

CyberGuard AI is a Flask-based web application designed to teach users how to spot phishing attempts and scam messages in a safe, engaging way. It combines:

- a phishing simulation challenge
- a scam message analyzer
- personalized risk insights
- a voice scam simulator experience
- an admin dashboard for analytics

The platform is built to make cybersecurity education feel practical and real rather than purely theoretical.

## 🚀 Features

- Real-world phishing simulation scenarios
- AI + rule-based scam detection
- Psychological trigger analysis (urgency, authority, reward, fear, links)
- Personalized vulnerability insights
- Adaptive learning experience
- Profile and result tracking
- Admin analytics view
- Responsive, modern UI

## 🛠️ Tech Stack

- Python
- Flask
- scikit-learn
- joblib
- HTML/CSS/JavaScript
- Gunicorn (for deployment)

## 📁 Project Structure

```text
ai-cyber-safety-mentor/
│
├── app.py                 # Main Flask application
├── phishing_dataset.py   # Scam message dataset
├── requirements.txt      # Python dependencies
├── Procfile              # Heroku deployment config
├── scam_model.pkl        # Trained scam detection model
├── vectorizer.pkl       # Text vectorizer
├── static/               # CSS and media assets
├── templates/            # HTML pages
└── temp_simulation.jsx   # Frontend simulation component
```

## ⚙️ Installation

1. Clone the repository
   ```bash
   git clone <your-repo-url>
   cd ai-cyber-safety-mentor
   ```

2. Create and activate a virtual environment
   ```bash
   python -m venv venv
   source venv/bin/activate
   ```

   On Windows PowerShell:
   ```powershell
   .\venv\Scripts\Activate.ps1
   ```

3. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```

## ▶️ Run the Application

Start the Flask app:

```bash
python app.py
```

Then open your browser at:

```text
http://127.0.0.1:5000/
```

## 🧪 How It Works

- The app analyzes messages using a hybrid model:
  - an ML-based classifier
  - a set of rule-based indicators for common scam patterns
- Users can practice by completing phishing challenges and scoring their response choices.
- After each session, the app generates behavioral insights and a personalized digital safety profile.

## 🌐 Deployment

This project includes a Heroku-style Procfile for deployment support:

```text
web: gunicorn app:app
```

You can deploy it on platforms like Heroku, Render, or Railway with Python support.

## 🤝 Contribution

Contributions are welcome. If you want to improve the experience, you can:

- add more scam categories
- expand the ML model training data
- improve the UI/UX
- add more educational content and challenge modes

## 📜 License

This project is available for educational and demonstration purposes.
