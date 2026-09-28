# 💰 Expense Tracker Project

Introducing a comprehensive full-stack MERN application engineered for personal finance management. Leveraging MongoDB, Express.js, React, and Node.js, this project delivers a secure and responsive interface for tracking income/expenses, visualizing financial data with analytics, and exporting records to Excel
---


## 🛠 Tech Stack

### Frontend

* **React** + **Vite**: Achieve rapid development and hot module reloading for your user interfaces.
* **Tailwind CSS**: Craft beautiful, mobile-first designs with a utility-first CSS framework.
* **Axios**: Streamline your HTTP requests for seamless data fetching.
* **Recharts**: Create compelling and interactive data visualizations.

### Backend

* **Node.js** & **Express.js**: The foundation for building scalable and efficient web APIs.
* **MongoDB Atlas** & **Mongoose**: Provides a powerful combination for flexible, cloud-based database management.
* **JWT**: Essential for implementing secure and token-based authentication.
* **Multer**: Simplifies the process of handling various file uploads.
* **xlsx**: Enables the dynamic creation and export of data into Excel spreadsheets.

---

## 🧾 Features

* 🔐 Secure Auth: JWT-powered login & registration.
* 👤 Access Control: Role-based user permissions.
* ➕ Financial Tracking: Add, view, delete income & expense entries.
* 📊 Data Visuals: Interactive charts on visual dashboards.
* 📁 Excel Export: Download income & expense records.
* 🖼️ Profile Images: Upload & store user profile pictures.
* 🌐 Responsive Design: Optimized for all devices.

---

## 📁 Folder Structure

```
Expense-Tracker-Project/
├── backend/       # Express.js API and MongoDB integration
├── frontend/      # React + Vite application
├── .gitignore      
└── README.md      # Project documentation
```

---

## 🚀 Getting Started Locally

### 1. Clone the Repository

```bash
git clone https://github.com/lovenew232/Expense-Tracker-Project.git
cd Expense-Tracker-Project
```

### 2. Backend Setup

```bash
cd backend
npm install
```
Users have to create a new cluster in MongoDB and get few keys.
Create a `.env` file in the backend folder with the following keys:

```
MONGO_URI=put_your_mongodb_uri
JWT_SECRET=put_your_jwt_secret
PORT=8000
```

Start the backend server:

```bash
npm start
```

### 3. Frontend Setup

```bash
cd ../frontend
npm install
```

Run the development server:

```bash
npm run dev
```
---

## 👨‍💻 Author

Developed by **Lovenew**
📌 [My GitHub Profile](https://github.com/lovenew232)

---
