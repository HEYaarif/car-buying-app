# 🚗 Second-hand Car Buying Application

A modern, web-based platform to simplify the process of buying and selling second-hand cars. Designed with a clean user interface, intuitive experience, and role-based functionality for admins and users.

---

## 📌 Table of Contents

📚 Overview
A quick summary of what the application is, who it’s for, and its purpose.

🛠️ Tech Stack
The list of technologies used to build the application, including frameworks, libraries, and tools.

✨ Features
A breakdown of core functionality available in the app for both users and admins.

🔐 Authentication
Explains how users log in via Google using Firebase Authentication.

👤 User Role
Describes what a regular user can do — search for cars, send purchase requests, etc.

🛠 Admin Role
Describes what an admin can manage — add/edit car listings, respond to user requests, etc.

📄 Pages
Lists the required and implemented pages of the application, such as login, dashboard, and listings.

🚀 Getting Started
Step-by-step guide to set up the project locally — including cloning, installing dependencies, setting up Firebase, and running the app.

📁 Project Structure
Explains the folder and file organization of the source code for easier navigation and understanding.

🧪 Future Improvements
Suggestions for enhancements and new features that can be implemented later to improve the app.

📸 Screenshots
A placeholder for visual examples of the app's user interface — like login, dashboard, and car listings (to be added once the UI is built).

📝 License
Information about how the project is licensed and what permissions users have to use or modify the code.



---

## 📚 Overview

This is a web-based application aimed at facilitating seamless buying and selling of second-hand cars. The app provides role-based functionalities:

- **Admins** can manage car listings, pricing, and user requests.
- **Users** can search for available cars and request to purchase them.

---

## 🛠️ Tech Stack

| Area        | Technology             |
|-------------|------------------------|
| Frontend    | React.js               |
| State Mgmt  | (Optional) Redux       |
| Language    | JavaScript / TypeScript (optional) |
| Authentication | Firebase Auth (Google Sign-In) |
| Database    | Firebase Firestore / Supabase |
| Hosting     | Firebase Hosting (optional) |

---

## ✨ Features

### 🔐 Authentication

- Google Sign-In using Firebase Authentication
- Role-based access (Admin and User)
- Session persistence

---

### 👤 User Role

- 🔍 **Search Cars:** Users can browse all available second-hand cars.
- 📩 **Send Request:** Interested users can request to buy a listed car.

---

### 🛠 Admin Role

- ➕ **Add New Car:** Add car listings with image, brand, model, year, and pricing.
- 📝 **Edit Car Details:** Modify existing listings, including price updates.
- 📬 **Manage Requests:** View and manage purchase requests made by users.

---

## 📄 Pages

Minimum of **three required pages**:

1. **Login Page:** Google Auth integration.
2. **Home / Listing Page:** View all cars.
3. **Admin Dashboard:** Car management and request handling.

_Optional_: Ignore additional pages from Figma unless required.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/second-hand-car-app.git
cd second-hand-car-app

Project Structure

src/
│
├── components/        # Reusable UI components
├── pages/             # Route-based pages (Login, Home, Dashboard)
├── services/          # Firebase/Supabase service logic
├── utils/             # Helper functions
├── context/           # Auth context and role management
├── App.tsx / App.jsx  # Main App component
└── main.tsx / main.jsx

🧪 Future Improvements
Email Notifications on Requests

Real-time Chat between Users and Admins

Search filters (Price, Year, Brand)

Responsive design enhancements

Admin Analytics Dashboard
