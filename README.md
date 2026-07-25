# 🛡️ InsureHub – AI Powered Insurance Comparison & Recommendation Platform

A full-stack Insurance Comparison and Recommendation Platform developed during an **Infosys Springboard Internship** as part of a **7-member collaborative team**. The application enables users to compare insurance policies, receive personalized AI-based recommendations, manage claims, and monitor their insurance activities through a modern dashboard.

> **Role:** Recommendation Engine Developer & Frontend Integration

---

## 📌 Project Overview

InsureHub is a modern insurance management platform designed to simplify the process of selecting insurance policies.

The platform allows users to:

- Compare multiple insurance policies
- Receive personalized policy recommendations
- View policy details
- Track insurance claims
- Manage active insurance plans
- Monitor dashboard statistics
- Access profile and account settings

The recommendation module intelligently analyzes user preferences such as budget and policy coverage to suggest the most suitable insurance plans.

---

# ✨ Features

### 👤 User Authentication

- Secure Login
- User Registration
- Session Management
- Profile Management

---

### 📊 Dashboard

- Active Plans Summary
- Claims Status
- Recommended Policies Count
- Recent Activity
- Quick Navigation Cards

---

### 📑 Policy Management

- Browse available insurance policies
- View premium details
- Coverage information
- Provider information
- Policy comparison

---

### 🤖 AI Recommendation System

The recommendation engine suggests policies based on:

- User Budget
- Coverage Amount
- Claim Settlement Ratio
- Risk Analysis
- Overall Match Score

Each recommendation displays:

- Match Percentage
- Risk Level
- Premium
- Coverage
- Claim Ratio
- Recommendation Reason
- Policy Features

---

### 🛡 Risk Assessment

Policies are categorized as:

- Low Risk
- Medium Risk
- High Risk

based on their claim settlement ratio.

---

### 📂 Claims Management

- File Insurance Claims
- Track Claim Status
- View Claim History

---

### 📈 Policy Analysis

The recommendation engine calculates a match score by considering:

- Budget Compatibility
- Coverage Value
- Claim Settlement Ratio

Policies are automatically ranked according to their overall score.

---

# 🧠 Recommendation Logic

The recommendation system evaluates each insurance policy using multiple factors.

### Match Score Calculation

✔ Budget Matching

- Premium within user budget
- Higher score for affordable policies

✔ Coverage Analysis

- Better coverage receives higher priority

✔ Claim Settlement Ratio

- Companies with better claim history receive additional score

The final score is normalized to **100%**, allowing users to easily compare policies.

---

# 🖥 User Interface

The application provides a modern and clean dashboard including:

- Dashboard Overview
- Policy Catalog
- Recommendation Page
- Claims Page
- Active Plans
- User Profile
- Settings

The interface is designed for ease of use with responsive layouts and intuitive navigation.

---

# 🏗 Architecture

```
Client (React + Vite)
        │
 REST API
        │
FastAPI Backend
        │
Recommendation Engine
        │
Policy Dataset
```

---

# 📂 Project Structure

```
insurance-crc-feb-26
│
├── client/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── context/
│   │   ├── data/
│   │   ├── features/
│   │   ├── hooks/
│   │   ├── layout/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── tests/
│   │   └── utils/
│
├── server/
│   ├── src/
│   │   ├── auth/
│   │   ├── claims/
│   │   ├── database/
│   │   ├── entities/
│   │   ├── routers/
│   │   ├── users/
│   │   ├── recommendation_engine.py
│   │   ├── models.py
│   │   └── main.py
│
└── README.md
```

---

# 💻 Technologies Used

## Frontend

- React.js
- Vite
- JavaScript
- CSS3
- React Router

---

## Backend

- Python
- FastAPI

---

## Database

- SQLite
- SQLAlchemy

---

## Tools

- Git
- GitHub
- Postman
- Docker
- Figma
- VS Code

---

# 👨‍💻 My Contribution

As a team member during the Infosys Springboard Internship, I was primarily responsible for designing and implementing the **Policy Recommendation Module**.

### My Responsibilities

- Developed the recommendation algorithm
- Designed policy scoring logic
- Implemented match percentage calculation
- Added risk level analysis
- Displayed personalized recommendations
- Integrated frontend recommendation page with backend APIs
- Tested recommendation workflow
- Participated in Git-based collaborative development

---

# 📈 Recommendation Algorithm

The recommendation engine evaluates policies based on:

```
Score =
Budget Match
+ Coverage Score
+ Claim Ratio Score
```

Policies are sorted from highest to lowest match percentage.

---

# 🚀 Future Improvements

- Machine Learning based recommendations
- User preference learning
- Premium prediction
- Policy comparison charts
- Email notifications
- Admin Dashboard
- Payment Integration
- Real-time analytics

---

# 📷 Screens

- Dashboard
  <img width="1528" height="875" alt="Screenshot 2026-07-25 213140" src="https://github.com/user-attachments/assets/9d554246-6b66-4439-bd7d-a1142fac14d6" />
- Policy Catalog
  <img width="1311" height="878" alt="Screenshot 2026-07-25 213159" src="https://github.com/user-attachments/assets/6c51acfb-dd39-4245-9540-b3024e8224db" />
- AI Recommendation Page
  <img width="597" height="903" alt="Screenshot 2026-07-25 213241" src="https://github.com/user-attachments/assets/32778efa-e1fc-4f28-beb1-03db13785633" />
- Claims Management
  <img width="1429" height="878" alt="Screenshot 2026-07-25 213254" src="https://github.com/user-attachments/assets/b7b1dcdb-efea-4721-9b41-acab13202dac" />
- User Profile
  <img width="1419" height="872" alt="Screenshot 2026-07-25 213309" src="https://github.com/user-attachments/assets/1d9910d6-0e48-4d1b-a5d2-8ed33185fc37" />
- Login & Signup
  <img width="1418" height="874" alt="Screenshot 2026-07-25 213326" src="https://github.com/user-attachments/assets/2c114b99-e02d-4a11-a537-e26c62382672" />


---

# 🎯 Learning Outcomes

Through this project, I gained practical experience in:

- Team Collaboration
- Git & GitHub Workflow
- Branch Management
- Pull Requests
- REST API Integration
- FastAPI Development
- React Frontend Development
- Recommendation System Design
- Problem Solving
- Agile Development

---

# 📜 Internship

Developed as part of the **Infosys Springboard Internship Program** through collaborative team development.

---

# 👩‍💻 Author

**Durga Mundkar**

Recommendation Engine Developer

Computer Science Engineering Student

MGM's College of Engineering, Nanded

---

⭐ If you found this project useful, consider giving it a Star.
