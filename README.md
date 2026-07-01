
# 🏥 MediMate – AI Powered Smart Healthcare System Using XAI

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Django](https://img.shields.io/badge/Django-5.x-green)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Naive%20Bayes-orange)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-purple)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview

MediMate is an AI-powered healthcare platform that combines hospital management features with an intelligent symptom checker chatbot. The platform helps patients manage appointments, access healthcare services, maintain medical records, and receive preliminary disease predictions based on their symptoms using Machine Learning.

The project focuses on improving accessibility, reducing waiting time, and providing users with quick health assistance through an intuitive web interface.

---

# ✨ Key Features

## 👨‍⚕️ Patient Module

- Patient Registration & Login
- Profile Management
- Book Doctor Appointments
- View Appointment History
- Download Medical Reports
- Manage Medical Records
- AI Symptom Checker

---

## 🩺 Doctor Module

- Doctor Registration
- Clinic Profile Setup
- Appointment Management
- View Patient Details
- Generate Prescriptions
- Manage Availability

---

## 🤖 AI Symptom Checker

The AI-powered chatbot enables users to:

- Enter symptoms using natural conversation
- Select symptoms from intelligent suggestions
- Predict the most probable disease
- Display confidence score
- View disease description
- Show suggestions
- Suggest medicine Classes
- Explain symptoms using Explainable AI (SHAP)

---

# 🧠 Machine Learning Model

### Algorithm Used

- Multinomial Naive Bayes

### Dataset

- Mendeley Symptoms-Disease Dataset

Dataset Statistics:

- **377 Diseases**
- **443 Symptoms**

---

# 📊 Explainable AI (XAI)

To improve transparency, MediMate integrates Explainable AI using **SHAP (SHapley Additive Explanations)**.

Features:

- Feature Importance Visualization
- Prediction Explanation
- Confidence Score

This allows users to understand why a particular disease was predicted.

---

# 💊 Medicine Recommendation

Medicine recommendations are verified using:

- WHO Essential Medicines List (Adults)
- WHO Essential Medicines List (Children)

The system maps predicted diseases with commonly recommended medicines for educational purposes only.

---

# 🛠️ Technology Stack

## Frontend

- HTML5
- CSS3
- Bootstrap 5
- JavaScript

## Backend

- Python
- Django

## Machine Learning

- Scikit-learn
- Pandas
- NumPy

## Explainable AI

- SHAP

## Database

- SQLite

---

# 📂 Project Structure

```
MediMate/
│
├── chatbot/
├── appointments/
├── doctors/
├── patients/
├── reports/
├── prescriptions/
├── media/
├── static/
├── templates/
│
├── manage.py
└── requirements.txt
```

---

# 🚀 Installation & Setup

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/MediMate-AI-Powered-Smart-Healthcare-System-Using-XAI.git
```

> Replace `your-username` with your GitHub username.

---

## 2️⃣ Navigate to the Project Directory

```bash
cd MediMate-AI-Powered-Smart-Healthcare-System-Using-XAI
```

---

## 3️⃣ Create a Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### macOS / Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## 4️⃣ Install Required Dependencies

```bash
pip install -r requirements.txt
```

---

## 5️⃣ Apply Database Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

---

## 6️⃣ (Optional) Create an Admin User

```bash
python manage.py createsuperuser
```

Follow the prompts to set the username, email, and password.

---

## 7️⃣ Start the Development Server

```bash
python manage.py runserver
```

---

## 8️⃣ Open the Application

Visit the following URL in your browser:

```
http://127.0.0.1:8000/
```

To access the Django Admin Panel:

```
http://127.0.0.1:8000/admin/
```

---

# 📷 Screenshots

<img width="1647" height="856" alt="image" src="https://github.com/user-attachments/assets/4b34c62a-1d3e-4c4e-aba9-d81f09812d63" />
<img width="1658" height="825" alt="image" src="https://github.com/user-attachments/assets/bfad72be-6d45-4f3b-8b3a-82cc3bfd5009" />
<img width="1600" height="683" alt="image" src="https://github.com/user-attachments/assets/8a745d34-8856-4c7c-bb23-85979163efff" />
<img width="1600" height="750" alt="WhatsApp Image 2026-06-30 at 10 38 52 PM" src="https://github.com/user-attachments/assets/955b861a-550c-4e54-a182-e9627380c82b" />
<img width="867" height="875" alt="WhatsApp Image 2026-06-30 at 10 38 52 PM (1)" src="https://github.com/user-attachments/assets/54397a5c-5319-4a29-aa17-77e1d97a251c" />


---

# 🎯 Future Enhancements

- Voice-based Symptom Checker
- Medical Image Analysis
- Disease Risk Prediction
- Telemedicine Video Consultation
- Drug Interaction Detection
- Health Analytics Dashboard
- Multi-language Support
- Wearable Device Integration

---

# 📚 Learning Outcomes

This project helped in gaining practical experience in:

- Full Stack Django Development
- Machine Learning Integration
- Explainable AI
- Healthcare System Design
- REST Architecture
- Database Management
- Authentication & Authorization
- Responsive UI Development

---

# 👩‍💻 Developed By

**Dipali Porje**

B.E. Artificial Intelligence & Data Science

---

# ⭐ If you like this project

Please give this repository a ⭐ on GitHub.

It motivates further development and open-source contributions.

---

# 📄 License

This project is developed for educational and research purposes.
