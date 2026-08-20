# 🚨 ResQAI Emergency Dashboard

The **ResQAI Emergency Dashboard** is the web-based monitoring interface of the ResQAI Crisis Response System.

It is designed to provide a centralized interface for viewing and managing emergency-related information and connecting the dashboard with the Firebase backend.

---

## 🌟 About

During a crisis, emergency information needs to be accessible and organized in one place.

The ResQAI Dashboard provides a web interface that can be used by authorized users or response teams to monitor emergency information received through the ResQAI system.

The dashboard is built using **React.js** and integrated with **Firebase** for cloud-based data management.

---

## ✨ Features

### 🚨 Emergency Monitoring

Provides a centralized dashboard for viewing emergency alerts and crisis-related information.

### 📊 Dashboard Interface

Displays emergency information in a structured and easy-to-understand interface.

### 🔥 Firebase Integration

The dashboard connects with Firebase to access and manage application data.

### ⚡ Real-Time Data

Firebase can be used to provide updated emergency information without requiring manual data synchronization.

### 🛡️ Secure Configuration

Firebase configuration and environment variables are kept outside the public source code wherever possible.

### 📱 Responsive Interface

The dashboard is designed as a web application and can be extended to support different screen sizes and devices.

---

## 🛠️ Technology Stack

| Technology | Purpose |
|------------|---------|
| React.js | Frontend framework |
| JavaScript | Application logic |
| HTML | Application structure |
| CSS | Styling and UI |
| Firebase | Backend and cloud services |
| Firestore | Cloud database |
| npm | Package management |
| Git & GitHub | Version control |

---

## 📁 Project Structure

```text
dashboard/
│
├── public/
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   └── robots.txt
│
├── src/
│   ├── App.js
│   ├── App.css
│   ├── App.test.js
│   ├── firebase.js
│   ├── index.css
│   ├── index.js
│   ├── logo.svg
│   ├── reportWebVitals.js
│   └── setupTests.js
│
├── .gitignore
├── package.json
├── package-lock.json
└── README.md
