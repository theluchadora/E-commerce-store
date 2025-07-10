# 🛍️ LD Shopper (E-Commerce App)

A complete **E-Commerce web application** built with a **React.js frontend**, **Node.js & Express backend**, and **MongoDB** for the database. It includes a dedicated **Admin Panel** for managing products, as well as user authentication, cart management, product filtering, and image uploads.

---

## 📦 Tech Stack

- **Frontend:** React.js, CSS  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB (with Mongoose)  
- **Authentication:** JSON Web Token (JWT)  
- **Image Upload:** Multer  
- **State Management:** React Context API  

---

## 📁 Project Structure


E-commerce-store/
│
├── backend/
│   ├── index.js
│   ├── upload/
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── Components/
│   │   ├── Context/
│   │   ├── Pages/
│   │   └── App.js
│   └── package.json
│
├── admin/
│   ├── src/
│   │   ├── Components/
│   │   └── Pages/
│   └── package.json
│
└── README.md


---

## ⚙️ Installation & Setup

### 📥 1️⃣ Clone the Repository:

git clone https://github.com/theluchadora/E-commerce-store.git
cd E-commerce-store


### 📦 2️⃣ Install Dependencies

#### Backend:

cd backend
npm install


#### Frontend:

cd ../frontend
npm install


#### Admin Panel:

cd ../admin
npm install


---

## 🔧 Database Configuration

This project uses **MongoDB Atlas** (or local MongoDB instance if preferred).  
The database connection string is **hardcoded in**:


backend/index.js

Locate the following line:
mongoose.connect("mongodb+srv://<yourusername>:<yourpassword>@cluster0.wb5aaly.mongodb.net/e-commerce");


And **replace**:
- `yourpassword` → your **MongoDB username**
- `yourpassword` → your **MongoDB password**


⚠️ **Important:**  
For production-grade deployment, you should move these credentials to a `.env` file and use `dotenv` to load them securely.


## 🚀 Running the Project

### 📦 Backend

cd backend
npm start

Runs at: [http://localhost:4000](http://localhost:4000)

---

### 📦 Frontend

cd frontend
npm start

Runs at: [http://localhost:3000](http://localhost:3000)

---

### 📦 Admin Panel

cd admin
npm start

Runs at: [http://localhost:5173](http://localhost:5173)

---

## 📌 Features

- ✅ User registration and login (with JWT)
- ✅ Add to Cart / Remove from Cart (cart persisted per user in database)
- ✅ Product management via Admin Panel (Add / Delete products)
- ✅ Image upload functionality for products (using Multer)
- ✅ Category-based product filtering
- ✅ New collection and popular products sections
- ✅ Fully integrated backend and frontend

---
.

