# 🍽️ Restaurant Recommendation System

A full-stack **Restaurant Recommendation Web Application** built using the **MERN stack (MongoDB, Express.js, React.js, Node.js)**.

The application helps users discover restaurants through a clean and interactive interface, while providing a complete full-stack architecture with a React frontend and Node.js/Express backend.

## 🌐 Live Demo

🚀 **Live Application:**
https://restaurant-recommendation-mern.vercel.app/
---

## 📌 Project Overview

The Restaurant Recommendation System is designed to provide users with a convenient platform for discovering and exploring restaurants.

The project demonstrates how a modern full-stack web application can connect a React-based frontend with a Node.js/Express backend and MongoDB database.

The application focuses on:

* 🍴 Restaurant discovery
* 🔍 Restaurant searching and exploration
* ⭐ Restaurant recommendations
* 👤 User interaction
* 🔐 Authentication
* 📱 Responsive user interface
* 🔄 Frontend-backend API integration
* 🗄️ Database-driven restaurant information

---

## ✨ Features

### 👤 User Features

* 🔐 User registration and login
* 👤 User account management
* 🍽️ Browse restaurants
* 🔎 Search and explore restaurants
* ⭐ View restaurant information
* 🎯 Get restaurant recommendations
* 📱 Responsive interface
* ⚡ Fast and interactive user experience

### 🏪 Restaurant Features

* Restaurant listing
* Restaurant details
* Food/category information
* Ratings and recommendation-oriented information
* Dynamic restaurant data

### 🔧 Full-Stack Features

* REST API integration
* MongoDB database connectivity
* React frontend
* Node.js backend
* Express.js API server
* Frontend-backend communication
* Environment-based configuration
* Production deployment

---

## 🛠️ Tech Stack

### Frontend

* **React.js**
* **JavaScript**
* **HTML5**
* **CSS3**
* **React Router**
* **Axios / API integration**

### Backend

* **Node.js**
* **Express.js**
* **REST APIs**

### Database

* **MongoDB**
* **Mongoose**

### Deployment

* **Vercel**

### Development Tools

* **Git**
* **GitHub**
* **VS Code**
* **npm**

---

## 🏗️ System Architecture

```text
                 ┌─────────────────────┐
                 │       User          │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │   React Frontend    │
                 │      (Frontend)     │
                 └──────────┬──────────┘
                            │
                         REST API
                            │
                            ▼
                 ┌─────────────────────┐
                 │   Express.js API    │
                 │      (Backend)      │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │      MongoDB        │
                 │      Database       │
                 └─────────────────────┘
```

---

## 📂 Project Structure

```text
restaurant-recommendation/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   ├── server.js
│   └── package.json
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── assets/
│   │   ├── services/
│   │   └── App.js
│   │
│   ├── package.json
│   └── ...
│
└── README.md
```

> The exact internal folders can vary depending on the latest version of the project.

---

# 🚀 Getting Started

Follow the steps below to run the project locally.

## 📋 Prerequisites

Make sure you have the following installed:

* Node.js
* npm
* MongoDB or MongoDB Atlas
* Git

Check your Node.js installation:

```bash
node --version
```

Check npm:

```bash
npm --version
```

---

## 📥 Clone the Repository

```bash
git clone https://github.com/yamini823/restaurant-recommendation.git
```

Navigate into the project:

```bash
cd restaurant-recommendation
```

---

# 🔙 Backend Setup

Navigate to the backend:

```bash
cd backend
```

Install dependencies:

```bash
npm install
```

Create a `.env` file inside the backend directory.

Example:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

> Use the actual environment variable names from your backend configuration.

Start the backend:

```bash
npm start
```

For development, if your project supports nodemon:

```bash
npm run dev
```

The backend will run on a local server such as:

```text
http://localhost:5000
```

---

# 🎨 Frontend Setup

Open another terminal.

Navigate to the frontend:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Create/configure the required environment variables.

For example:

```env
REACT_APP_API_URL=http://localhost:5000
```

Then start the frontend:

```bash
npm start
```

The application will generally be available at:

```text
http://localhost:3000
```

---

# 🔄 How the Application Works

The application follows a client-server architecture.

### Step 1 — User Interaction

The user opens the application and interacts with the React frontend.

### Step 2 — Frontend Request

When the user performs an action such as searching or requesting restaurant information, the frontend sends a request to the backend API.

### Step 3 — Backend Processing

The Express.js backend receives the request and processes the required operation.

### Step 4 — Database Interaction

The backend communicates with MongoDB through Mongoose to retrieve or update restaurant/user information.

### Step 5 — Response

The backend sends the requested data back to the React frontend.

### Step 6 — UI Update

React processes the response and dynamically updates the interface.

```text
User
 ↓
React UI
 ↓
API Request
 ↓
Express.js
 ↓
MongoDB
 ↓
Express.js
 ↓
API Response
 ↓
React UI
```

---

# 🔐 Authentication

The application includes user authentication functionality.

The authentication flow follows:

```text
User Registration
       ↓
User Login
       ↓
Authentication
       ↓
Token / Session
       ↓
Protected Application Features
```

Authentication helps protect user-specific functionality and ensures that only authorized users can access protected resources.

---

# 🎯 Recommendation System

The core objective of this project is to help users discover restaurants that match their interests.

The recommendation functionality can use available restaurant information and user interaction data to present relevant restaurant choices.

The system is designed to make restaurant discovery easier by reducing the effort required to manually search through large numbers of restaurants.

---

# 📱 Responsive Design

The application is designed to provide a smooth experience across different screen sizes.

It can be accessed through:

* 💻 Desktop
* 💻 Laptop
* 📱 Mobile
* 📟 Tablet

---

# ☁️ Deployment

The frontend application is deployed using **Vercel**.

### Production Application

🚀 https://restaurant-recommendation-mern.vercel.app/

The project demonstrates the deployment of a full-stack web application with the frontend connected to the backend services and database.

---

# 🔑 Environment Variables

For security reasons, sensitive information should not be committed to GitHub.

Typical environment variables may include:

```env
PORT=
MONGODB_URI=
JWT_SECRET=
API_URL=
```

Never commit:

```text
.env
```

or expose:

* Database credentials
* JWT secrets
* API keys
* Private tokens

---

# 🧪 Testing the Application

After starting the application:

1. Open the frontend.
2. Register a new account.
3. Log in.
4. Explore available restaurants.
5. Search/browse restaurants.
6. View restaurant information.
7. Explore recommendations.
8. Test user-specific functionality.

---

# 📊 Key Learning Outcomes

This project helped demonstrate practical experience with:

* Full-stack web development
* MERN architecture
* React component development
* REST API development
* Express.js backend development
* MongoDB database integration
* Mongoose data modeling
* Authentication
* Frontend-backend integration
* Environment variables
* Git and GitHub
* Production deployment
* Vercel deployment

---

# 🔮 Future Enhancements

The project can be extended with additional features such as:

* 🤖 AI-powered restaurant recommendations
* 📍 Location-based restaurant recommendations
* 🗺️ Google Maps integration
* ❤️ Favorite restaurants
* ⭐ User reviews and ratings
* 🔔 Personalized notifications
* 🔎 Advanced restaurant filtering
* 💰 Price-range filtering
* 🍕 Cuisine-based recommendations
* 📊 Personalized recommendation history
* 📱 Progressive Web App support
* ☁️ Improved cloud deployment architecture

---
