# 🎟️ Ventory - Full-Stack Event Booking Platform

Ventory is a full-stack **MERN event booking platform** that allows users to discover events, register, and submit secure booking requests. The platform also provides an administrative dashboard for managing events, bookings, users, and payment status.

## ✨ Features

### 👤 User Authentication
- Secure user registration and login
- JWT-based authentication
- Password hashing using bcrypt
- Email OTP verification

### 🎫 Event Management
- Browse available events
- Create and manage events through the admin dashboard
- Support for free and paid events
- Event categories and descriptions
- Event images
- Date and seating capacity management

### 📋 Smart Booking System
- Secure OTP verification before booking
- Booking requests are initially placed in a pending state
- Admin can approve or reject booking requests
- Seat availability validation
- Protection against overbooking
- Users can view and cancel their bookings

### 👨‍💼 Admin Dashboard
- Create, update, and delete events
- Manage booking requests
- Confirm or reject bookings
- Track payment status
- View total bookings and revenue
- Monitor confirmed paid clients

### 📧 Email Notifications
- OTP delivery through email
- Booking confirmation emails
- Automated notifications using Nodemailer

### 🎨 User Interface
- Responsive React-based interface
- Tailwind CSS styling
- Clean and modern UI
- React Icons
- Smooth user experience

---

## 🛠️ Tech Stack

### Frontend
- React.js
- JavaScript
- Tailwind CSS
- React Router
- Axios
- Vite

### Backend
- Node.js
- Express.js
- JWT
- bcrypt
- Nodemailer

### Database
- MongoDB
- Mongoose

### Tools
- Git & GitHub
- Postman

---

## 📁 Project Structure

```text
Ventory-MERN/
│
├── client/
│   ├── src/
│   │   ├── components/
│   │   ├── context/
│   │   ├── pages/
│   │   ├── utils/
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── package.json
│   └── vite.config.js
│
├── server/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   ├── server.js
│   └── package.json
│
├── dfd.png
├── fc.png
├── package.json
├── README.md
└── SETUP_GUIDE.md
