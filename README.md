# 🚨 ResQAI — Real Time Crisis Response System

> **ResQAI** is a technology-driven emergency response platform designed to improve disaster awareness, emergency communication, and coordination between citizens and response teams.

The system aims to provide a centralized platform where emergency alerts, incident information, and response-related updates can be managed efficiently.

---

## 🌍 Problem Statement

During natural and human-made disasters, people often face difficulties such as:

* Lack of timely emergency information
* Delayed communication with response teams
* Difficulty reporting incidents
* Scattered information from different sources
* Limited awareness about nearby emergencies
* Challenges in coordinating rescue and response activities

Traditional emergency-response systems may not provide a fast and centralized way to connect affected citizens with response authorities.

**ResQAI** aims to address these challenges through a centralized digital platform.

---

## 💡 Our Solution

ResQAI provides a platform for managing and communicating emergency situations through a combination of:

* 🚨 Emergency alerts
* 📍 Incident reporting
* 🤖 AI-assisted emergency information
* 📊 Emergency dashboard
* 🔥 Firebase-based data management
* 📱 Citizen-facing application
* 🛡️ Centralized crisis information

The goal is to reduce communication delays and make emergency information easier to access and manage.

---

## ✨ Key Features

### 🚨 Emergency Alerts

Users can receive information about reported emergencies and active incidents.

### 📍 Incident Reporting

Citizens can report emergency situations and provide relevant information to help response teams understand the situation.

### 🤖 AI-Assisted Response

AI can assist in processing emergency-related information and helping users understand the situation more efficiently.

### 📊 Emergency Dashboard

The dashboard provides a centralized interface for monitoring and managing emergency information.

### 🔥 Firebase Integration

Firebase is used for backend services and data management, allowing the application to work with centralized real-time data.

### 📱 Cross-Platform Application

The project includes a Flutter-based application for providing the citizen-facing interface.

### 🧭 Centralized Crisis Information

Emergency-related information can be organized in one platform instead of being scattered across multiple communication channels.

---

## 🏗️ Project Architecture

```text
                    ┌──────────────────────┐
                    │       Citizens       │
                    │   Mobile Application │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │      Firebase        │
                    │ Authentication/Data  │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │     ResQAI Dashboard │
                    │  Emergency Monitoring│
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │ Response / Rescue    │
                    │       Teams          │
                    └──────────────────────┘
```

---

## 🛠️ Technology Stack

### Frontend — Dashboard

* React.js
* JavaScript
* HTML
* CSS

### Mobile Application

* Flutter
* Dart

### Backend / Cloud

* Firebase
* Firebase Firestore
* Firebase Authentication

### Development Tools

* Git
* GitHub
* Visual Studio Code
* npm

---

## 📁 Project Structure

```text
APNcodexa/
│
├── app/                         # Flutter mobile application
│   ├── android/
│   ├── ios/
│   ├── lib/
│   │   └── main.dart
│   ├── web/
│   ├── windows/
│   ├── macos/
│   ├── linux/
│   ├── test/
│   └── pubspec.yaml
│
├── dashboard/                   # React emergency dashboard
│   ├── public/
│   │   ├── favicon.ico
│   │   ├── index.html
│   │   ├── logo192.png
│   │   ├── logo512.png
│   │   ├── manifest.json
│   │   └── robots.txt
│   │
│   ├── src/
│   │   ├── App.js
│   │   ├── App.css
│   │   ├── firebase.js
│   │   ├── index.js
│   │   ├── index.css
│   │   └── ...
│   │
│   ├── package.json
│   ├── package-lock.json
│   ├── .gitignore
│   └── README.md
│
└── FIRESTORE_STRUCTURE.md
```

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

* Node.js
* npm
* Git
* Flutter SDK (for the mobile application)
* A Firebase project

---

# 📊 Running the Dashboard

Navigate to the dashboard directory:

```bash
cd dashboard
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm start
```

The React dashboard will normally be available at:

```text
http://localhost:3000
```

---

# 📱 Running the Flutter Application

Navigate to the application directory:

```bash
cd app
```

Install Flutter dependencies:

```bash
flutter pub get
```

Run the application:

```bash
flutter run
```

Make sure a compatible emulator, physical device, or desktop/web target is available.

---

# 🔥 Firebase Configuration

ResQAI uses Firebase for cloud-based services.

The Firebase configuration should **not** be committed with sensitive environment variables or private credentials.

For local development, create the required environment/configuration file locally.

Example:

```text
dashboard/
└── .env
```

Make sure `.env` is included in `.gitignore`:

```text
.env
```

> ⚠️ Never commit private credentials, service-account keys, passwords, or other sensitive secrets to GitHub.

---

# 🔐 Security

Security is an important part of an emergency-response platform.

The project should follow these practices:

* Keep environment variables private
* Never commit Firebase service-account credentials
* Use Firebase Security Rules
* Restrict database access appropriately
* Validate user input
* Use authentication for protected functionality
* Avoid exposing sensitive user information
* Regularly review API-key restrictions and permissions

---

# 🧪 Testing

For the React dashboard:

```bash
cd dashboard
npm test
```

For Flutter:

```bash
cd app
flutter test
```

---

# 🌟 Impact

ResQAI is designed to contribute to a faster and more organized emergency-response ecosystem.

### Social Impact

* Improves access to emergency information
* Helps citizens report incidents
* Supports better communication
* Encourages disaster awareness
* Helps organize crisis-related information

### Technological Impact

* Combines AI with emergency-response workflows
* Uses cloud-based data management
* Provides a centralized emergency dashboard
* Creates a foundation for future predictive capabilities

### Future Impact

The platform can potentially be extended with:

* Real-time location tracking
* Geospatial emergency mapping
* AI-based risk prediction
* Disaster severity classification
* Automated emergency notifications
* Weather and environmental data integration
* Resource and rescue-team tracking
* Multilingual emergency assistance
* Offline emergency reporting

---

# 🔮 Future Scope

ResQAI can be expanded into a more comprehensive disaster-management platform.

Possible future improvements include:

### 🗺️ Real-Time Crisis Map

Display active incidents on an interactive map.

### 🌦️ Environmental Data Integration

Integrate weather, rainfall, flood, earthquake, and other environmental data.

### 🤖 Advanced AI Prediction

Use machine-learning models to identify patterns and estimate potential risks.

### 📍 Geolocation-Based Alerts

Send relevant alerts based on the user's location.

### 🚑 Rescue Resource Management

Track available rescue teams, vehicles, shelters, and emergency resources.

### 🌐 Multilingual Support

Provide emergency assistance in multiple Indian languages.

### 📡 Offline Support

Allow users to create emergency reports even with limited connectivity and synchronize them when connectivity is restored.

---

# 👥 Team

## APNcodexa

**Project:** ResQAI — AI-Powered Crisis Response System

The project is developed as a collaborative solution focused on improving emergency communication, awareness, and response coordination.

---

# 🎯 Project Vision

> **"Turning emergency information into coordinated action."**

ResQAI aims to use technology, AI, and cloud infrastructure to make emergency response more connected, accessible, and efficient.

---

## ⭐ Acknowledgements

We would like to acknowledge the open-source technologies and platforms that support this project, including:

* React
* Flutter
* Firebase
* JavaScript
* Dart
* GitHub
* Node.js

---
## 📜 License

This project is developed for educational, innovation, and hackathon purposes.

If you intend to use or distribute this project commercially, review and add an appropriate open-source or proprietary license.

---

with ❤️ by Team APNcodexa**
