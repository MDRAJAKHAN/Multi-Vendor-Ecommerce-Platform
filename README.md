# Hi there, I'm MD RAJA KHAN 👋

Welcome to my GitHub profile! I am an aspiring web developer passionate about building clean, responsive, and user-friendly web applications.

# Multi-Vendor Ecommerce Platform 🛒

A robust and scalable web application built using the MERN stack that enables multiple vendors to set up individual storefronts, manage products, and track orders within a single unified marketplace. 

---

## ✨ Features

- Real-time multi-vendor dashboard and inventory management
- Customer shopping cart and secure checkout process
- Optimized system stability and rendering speed by integrating Role-Based Access Control (RBAC) to securely separate Admin, Vendor, and Customer actions
- Advanced product discovery utilizing custom debounced search algorithms
- Seamless browsing experience featuring asynchronous UI loaders and a responsive interface built with Tailwind CSS
- Secure payment gateway integration
- Image uploading and management for product listings
- Scalable MongoDB database structure for large inventories

---

## 🛠 Tech Stack

### Frontend
- React.js
- Tailwind CSS
- Axios
- React Router DOM
- Redux Toolkit

### Backend
- Node.js
- Express.js
- JWT Authentication
- Bcrypt.js
- Multer (for file uploads)

### Database
- MongoDB
- Mongoose

---

# 📂 Project Structure

```bash
ecommerce-project/
│
├── frontend/
│
└── backend/
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone https://github.com/MDRAJAKHAN/multi-vendor-ecommerce-platform.git
```

---

# 🚀 Backend Setup

## Go to backend folder

```bash
cd backend
```

## Install dependencies

```bash
npm install
```

## Create `.env` file

```env
MONGO_URI=mongodb://127.0.0.1:27017/ecommerceDB
JWT_SECRET=your_jwt_secret_key
STRIPE_SECRET=your_stripe_test_key
CLOUDINARY_URL=your_cloudinary_url
```

## Start backend server

```bash
node server.js
```

Backend runs on:

```bash
http://localhost:5000
```

---

# 💻 Frontend Setup

## Open new terminal

```bash
cd frontend
```

## Install dependencies

```bash
npm install
```

## Start frontend

```bash
npm start
```

Frontend runs on:

```bash
http://localhost:3000
```

---

# 📦 Required Packages

## Frontend Packages

```bash
npm install axios react-router-dom @reduxjs/toolkit react-redux @stripe/react-stripe-js @stripe/stripe-js
```

```bash
npm install -D tailwindcss postcss autoprefixer
```

---

## Backend Packages

```bash
npm install express mongoose cors dotenv bcryptjs jsonwebtoken stripe multer cloudinary
```

---

# 🎯 How It Works

1. Users can register as either a Customer or a Vendor.
2. Vendors access a private dashboard to create listings and upload product images.
3. Customers browse the marketplace, filter products, and add items to their cart.
4. The system securely processes payments during checkout using integrated APIs.
5. Revenue is correctly attributed to the specific vendors who made the sale.
6. Customers and Vendors can track order fulfillment statuses from their respective profiles.

---

# 🌍 APIs Used

- Stripe API for secure payment processing
- Cloudinary API for cloud-based product image storage

---

# 📸 Future Enhancements

- AI-based product recommendations
- Comprehensive sales analytics dashboard for vendors
- Multi-currency and multi-language support
- Social media single sign-on (SSO)
- Native mobile application integration

---

# 👨‍💻 Author

## MD RAJA KHAN

- LinkedIn: https://linkedin.com/in/md-raja-khan-6b9070226
- GitHub: https://github.com/MDRAJAKHAN

---
