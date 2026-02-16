![Auth Shop Screenshot](https://i.ibb.co/pB83QZbp/ss-website.png)

# 🛒 Auth Shop – Next.js Full Stack E-Commerce Application

A modern, fully responsive **Authentication + Product Management** web application built with **Next.js (App Router), NextAuth.js, and Express.js**.  
The platform includes secure authentication, protected routes, full product CRUD functionality, search system, and a polished UI with smooth animations and micro-interactions.

---

## 🚀 Live Demo

🌍 Live Website: https://gadgethub-frontend-w84a.vercel.app/  
💻 Client Repository: https://github.com/RupomPB/gadgethub-frontend  
🖥 Server Repository: https://github.com/RupomPB/gadgethub-server  

---

## 📌 Project Overview

Auth Shop demonstrates a production-ready **full-stack architecture** using Next.js frontend and Express backend.

The application provides:

- Secure authentication (Google + Credentials)
- Public & Protected route handling
- Add / Manage Products (CRUD)
- Product search system
- Fully responsive UI with animations
- Clean layout with modern UX principles

---

## 🏗 Application Architecture

**Frontend (Next.js – App Router)**  
↓ API Requests (Axios)  
**Backend (Express.js)**  
↓  
**MongoDB Database**

Authentication handled via **NextAuth.js**

---

## 🔐 Authentication System

- Google OAuth Login  
- Email & Password Login  
- Session management using NextAuth.js  
- Protected routes with redirection logic  
- Persistent authentication state  

---

## 🛍 Product Management System

### ➕ Add Product (Protected)
Only authenticated users can access.

Fields:
- Title  
- Short Description  
- Full Description  
- Price  
- Date  
- Priority  
- Image URL  

On successful submission → Confirmation message / Toast notification.

---

### 📋 Manage Products (Protected)

- Displays all products  
- Clean responsive table / grid layout  
- Actions:
  - View Details  
  - Delete Product  

---

### 🔎 Item List Page

- Page Title & Description  
- Search functionality  
- Minimum 6 product cards  
- Each card contains:
  - Product Image  
  - Title  
  - Short Description (ellipsis)  
  - Price / Meta Info  
  - Details Button  

---

### 📄 Item Details Page

- Large Banner Image  
- Full Product Description  
- Meta Information (price, date, priority)  
- Back Navigation  

---

## 🏠 Landing Page Structure (7 Sections)

### ✔ Navbar
- Logo  
- 4+ Navigation Routes  
- Login / Register  
- After Login: User Info, Add Product, Manage Products  
- Sticky & Fully Responsive  

### ✔ Hero Section
- Headline  
- Subtitle  
- Call-To-Action Button  
- Optional background visuals  

### ✔ Additional Sections (Card-based Layout)
Examples:
- Features  
- Popular Products  
- Testimonials  
- Promotional Banner  

(All sections use uniform cards with hover effects.)

### ✔ Footer
- Useful links  
- Social icons  
- Copyright  

---

## 🎨 UI & UX Highlights

- Fully responsive design  
- Clean layout system  
- Smooth animations using Framer Motion  
- Micro-interactions for enhanced user experience  
- Modern component-based structure  

---

## 🛠 Tech Stack

### Frontend
- Next.js (App Router)  
- React 19  
- NextAuth.js  
- Tailwind CSS  
- DaisyUI  
- Axios  
- SweetAlert2  
- Framer Motion  
- React Icons  
- React Simple Typewriter  
- React Slick + Slick Carousel  
- React Responsive Carousel  
- React Fast Marquee  

### Backend
- Express.js  
- MongoDB  

---

## 📂 Project Structure

### Client
```
app/
components/
lib/
hooks/
context/
```

### Server
```
routes/
controllers/
models/
middleware/
config/
```

---

## ⚡ Performance & Best Practices

- Modular folder structure  
- Secure authentication flow  
- Protected route handling  
- Optimized API requests  
- Clean reusable UI components  
- Production-ready deployment  

---

## 📈 Future Improvements

- Role-based admin panel  
- Product editing functionality  
- Pagination system  
- Image upload (Cloud storage)  
- Advanced filtering & sorting  

---

## 👨‍💻 Developer

Rupom PB  
Full-Stack Developer  

Focused on building secure, scalable, and production-ready web applications.

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub.
