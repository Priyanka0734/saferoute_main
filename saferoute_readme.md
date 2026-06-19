<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" style="height:64px;margin-right:32px"/>

# SafeRoute

Overview
SafeRoute is a safety-focused route recommendation platform that helps users choose the safest route instead of only the shortest route.
The system analyzes safety-related factors such as reported incidents, lighting conditions, crowd density, and historical safety information to provide route safety recommendations.
Core Features
Route Safety Analysis
Source and destination input
Multiple route evaluation
Safety score generation
Safe route recommendation
Safety Visualization
Routes are displayed using:
Green → Safe
Orange → Moderate
Red → Dangerous
Community Reporting
Users can report:
Harassment
Stalking
Poor Lighting
Unsafe Areas
Suspicious Activities
Emergency Contact Management
Users can:
Add emergency contacts
Edit emergency contacts
Delete emergency contacts
SOS Assistance
One-tap SOS activation
Live location sharing
Emergency contact alerts
AI Components
K-Means Clustering
Used for identifying and grouping locations into:
High Risk Zones
Medium Risk Zones
Low Risk Zones
This helps visualize unsafe areas on the map.
Logistic Regression
Used for route safety prediction.
Factors considered:
Incident frequency
Crowd density
Lighting conditions
Historical safety data
Output:
Safe
Moderate
Dangerous
Main Modules
Authentication Module
Dashboard
Route Safety Module
Community Reporting Module
Emergency Contact Module
SOS Module
AI Prediction Module
Admin Module
Future Enhancements
Emergency Bypass System
Hidden emergency activation through gestures, button combinations, or shortcuts to instantly alert emergency contacts and emergency services.
Intel OpenVINO Integration
Future integration of Intel OpenVINO Toolkit for:
Crowd density estimation
CCTV analytics
Suspicious activity detection
Real-time risk assessment
Live Guardian Tracking
Real-time journey monitoring by trusted contacts.
Voice Activated SOS
Hands-free emergency activation using predefined voice commands.
Automatic Safety Check-In
Automatic alerts when users fail to confirm safe arrival.
Project Goal
To provide safer travel experiences by combining route analysis, community-driven safety information, emergency assistance, and AI-powered safety prediction in a single platform.

generate a readme.md file for this and also add tech stack - react and django

```markdown
# SafeRoute

<p align="center">
  <strong>Safety-focused route recommendation platform</strong>
</p>

<p align="center">
  Choose the safest route instead of only the shortest route.
</p>

---

## 📋 Overview

SafeRoute is a safety-focused route recommendation platform that helps users choose the safest route instead of only the shortest route. The system analyzes safety-related factors such as reported incidents, lighting conditions, crowd density, and historical safety information to provide route safety recommendations.

## 🎯 Project Goal

To provide safer travel experiences by combining route analysis, community-driven safety information, emergency assistance, and AI-powered safety prediction in a single platform.

---

## ✨ Core Features

### Route Safety Analysis
- Source and destination input
- Multiple route evaluation
- Safety score generation
- Safe route recommendation

### Safety Visualization
Routes are displayed using color coding:
- 🟢 **Green** → Safe
- 🟠 **Orange** → Moderate
- 🔴 **Red** → Dangerous

### Community Reporting
Users can report:
- Harassment
- Stalking
- Poor Lighting
- Unsafe Areas
- Suspicious Activities

### Emergency Contact Management
Users can:
- Add emergency contacts
- Edit emergency contacts
- Delete emergency contacts

### SOS Assistance
- One-tap SOS activation
- Live location sharing
- Emergency contact alerts

---

## 🤖 AI Components

### K-Means Clustering
Used for identifying and grouping locations into:
- **High Risk Zones**
- **Medium Risk Zones**
- **Low Risk Zones**

This helps visualize unsafe areas on the map.

### Logistic Regression
Used for route safety prediction with the following factors:
- Incident frequency
- Crowd density
- Lighting conditions
- Historical safety data

**Output:** Safe | Moderate | Dangerous

---

## 📦 Main Modules

1. **Authentication Module**
2. **Dashboard**
3. **Route Safety Module**
4. **Community Reporting Module**
5. **Emergency Contact Module**
6. **SOS Module**
7. **AI Prediction Module**
8. **Admin Module**

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|------------|
| **Frontend** | React |
| **Backend** | Django |
| **AI/ML** | K-Means Clustering, Logistic Regression |
| **Database** | Django ORM (SQLite/PostgreSQL) |

---

## 🚀 Future Enhancements

### Emergency Bypass System
Hidden emergency activation through gestures, button combinations, or shortcuts to instantly alert emergency contacts and emergency services.

### Intel OpenVINO Integration
Future integration of Intel OpenVINO Toolkit for:
- Crowd density estimation
- CCTV analytics
- Suspicious activity detection
- Real-time risk assessment

### Live Guardian Tracking
Real-time journey monitoring by trusted contacts.

### Voice Activated SOS
Hands-free emergency activation using predefined voice commands.

### Automatic Safety Check-In
Automatic alerts when users fail to confirm safe arrival.

---

## 📁 Project Structure

```

SafeRoute/
├── frontend/                 \# React application
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── utils/
│   ├── package.json
│   └── README.md
├── backend/                  \# Django application
│   ├── safe_route/
│   │   ├── models/
│   │   ├── views/
│   │   ├── serializers/
│   │   └── ai_modules/
│   ├── manage.py
│   └── requirements.txt
├── README.md
└── .gitignore

```

---

## 🏃 Getting Started

### Prerequisites
- Node.js 16+ and npm
- Python 3.8+
- Django 4.0+

### Frontend Setup (React)

```bash
cd frontend
npm install
npm start
```


### Backend Setup (Django)

```bash
cd backend
python -m pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```


---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 📞 Contact

For questions or support, please open an issue in the repository.

---

<p align="center">
  <strong>SafeRoute</strong> — Making travel safer for everyone 🛡️
</p>
```
```

