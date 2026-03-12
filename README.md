---

# 🛒 Full Stack E-Commerce Website

A full-stack e-commerce web application built with **React**, **Node.js**, **Express**, and **MongoDB**, featuring a customer storefront, admin dashboard, and secure backend APIs.

---

## 📁 Project Structure

```
Full-Stack-E-commerce-Website/
│
├── frontend/        # Customer-facing website
├── admin/           # Admin dashboard
├── backend/         # REST API & database logic
└── README.md
```

---

## ✨ Features

### 👤 User (Frontend)

* User authentication (JWT)
* Browse products
* Search products
* Add products to cart
* Update cart quantity
* Place orders
* Cash on Delivery (COD)
* Stripe payment integration
* View order history

---

### 🛠 Admin Panel

* Admin authentication
* Add / update / delete products
* View all orders
* Update order status
* Manage product inventory

---

### ⚙ Backend

* RESTful API using Express
* JWT-based authentication & authorization
* MongoDB database with Mongoose
* Cart management
* Order processing
* Stripe Checkout integration
* Secure middleware architecture

---

## 🧰 Tech Stack

### Frontend

* React
* React Router
* Context API
* Axios
* Tailwind CSS
* React Toastify

### Admin

* React
* Axios
* Tailwind CSS

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT
* Stripe API
* Cloudinary (image upload)

---

## 🚀 Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/Full-Stack-E-commerce-Website.git
cd Full-Stack-E-commerce-Website
```

---

## 🔧 Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file in the **backend** folder:

```env
PORT=
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

Run backend:

```bash
npm run server
```

Backend will run on:

```
http://localhost:
```

---

## 🎨 Frontend Setup

```bash
cd frontend
npm install
```

Create a `.env` file:

```env
VITE_BACKEND_URL=http://localhost:
```

Run frontend:

```bash
npm run dev
```

Frontend runs on:

```
http://localhost:
```

---

## 🧑‍💼 Admin Panel Setup

```bash
cd admin
npm install
```

Create a `.env` file:

```env
VITE_BACKEND_URL=http://localhost:
```

Run admin panel:

```bash
npm run dev
```

Admin panel runs on:

```
http://localhost:
```

---

## 🧪 API Testing

* Use **Postman** or **Thunder Client**
* JWT token must be passed in headers:


## 💳 Payment Integration

* Stripe Checkout
* Minimum charge limit applies (Stripe requirement)
* Currency handled at backend level
* Successful payment redirects to order verification page

---

## 📝 Notes

* Cart is synced between frontend and database
* Admin routes are protected
* Middleware-based authentication
* Clean separation of frontend, backend, and admin

---

## 📌 Future Improvements

* Razorpay 
* Order cancellation
* User profile page
* Product reviews & ratings
* Email notifications

---

## 🤝 Contributing

Pull requests are welcome.
For major changes, please open an issue first to discuss what you’d like to change.

---

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.
