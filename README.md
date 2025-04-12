# 🍽️ Food Ordering Application

![React](https://img.shields.io/badge/frontend-React%20%2B%20Vite-blue)
![Firebase](https://img.shields.io/badge/auth-Firebase-orange)
![Java](https://img.shields.io/badge/backend-Java-green)
![License](https://img.shields.io/github/license/RathoreAbhay/FoodOrderingApplication)
![Repo Size](https://img.shields.io/github/repo-size/RathoreAbhay/FoodOrderingApplication)

A modern, responsive Food Ordering Application that allows users to browse menus, add food items to the cart, and securely place orders online.  
Built with **React + Vite** for the frontend, **Firebase OAuth** for user authentication, **Java-based backend** for business logic and API services, and a chatbot integrated via **Chatbase.co** for real-time customer interaction.

---

## 🚀 Features

- 🔐 **Secure Authentication** using Firebase OAuth
- 📦 **Real-time Cart Management**
- 🛒 **Food Listing & Menu Categories**
- 💳 **Razorpay Payment Gateway** integration (if applicable)
- 💬 **Chatbot Integration** powered by [Chatbase.co](https://www.chatbase.co/)
- 📊 **Order History** & Transaction Records
- 📱 **Responsive Design** — mobile and desktop friendly

---

## 🛠️ Tech Stack

**Frontend**
- React.js
- Vite
- Tailwind CSS (or CSS/SCSS if used)
- Firebase Authentication (OAuth)
- Chatbase Chatbot Integration

**Backend**
- Java (Spring Boot or plain Java APIs)

**Other Integrations**
- Razorpay (for payment)
- Firebase Hosting

---


## 📂 Project Structure
```text
FoodOrderingApplication/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.jsx
│   │   └── main.jsx
│   └── vite.config.js
│
├── backend/
│   ├── src/
│   │   └── main/
│   │       └── java/
│   │           └── com/
│   │               └── foodorder/
│   │                   ├── controllers/
│   │                   ├── services/
│   │                   └── models/
│   ├── application.properties
│   └── pom.xml
│
└── README.md
```

---

## 🔧 Getting Started

### 📌 Prerequisites
- Node.js & npm
- Java JDK 17+
- Firebase Project & API keys
- Chatbase Account & chatbot embed link

### 📥 Installation

#### Frontend

```bash
cd frontend
npm install
npm run dev
```

#### Backend

```bash
cd backend
./mvnw spring-boot:run
```

---

## 🔑 Firebase Configuration
- Create a Firebase project at Firebase Console
- Enable Authentication > Sign-in method > Choose OAuth providers (Google, Facebook, etc.)
- Copy the config object and replace it inside firebase.js or your config file in src/
- Set your authentication rules in Firebase.

---

## 🤖 Chatbase Integration
- Sign up at Chatbase.co
- Create a chatbot and get the embed code
- Place the chatbot widget code inside your index.html or App.jsx

## 📄 License
This project is licensed under the MIT License.

## 👨‍💻 Author
Abhay Rathore

## ⭐ Show Your Support
If you like this project, give it a ⭐ on GitHub!
