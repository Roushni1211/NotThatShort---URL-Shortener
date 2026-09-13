# 🔗 NotThatShort – URL Shortener

NotThatShort is a full-stack URL shortening application that converts long URLs into short, shareable links.

The application provides secure authentication, URL management, link analytics, QR code generation, bulk URL shortening, and a responsive user dashboard.

---

## 🚀 Features

### 🔗 URL Shortening
- Convert long URLs into short links
- Redirect users from short URLs to original URLs
- Generate unique short URLs
- Manage created links from the dashboard

### 📊 Link Analytics
- Track link usage
- View URL-related analytics
- Access analytics through a dedicated dashboard modal

### 🔐 Authentication & Security
- User registration and login
- JWT-based authentication
- Secure protected routes
- Email verification
- Forgot password functionality
- Reset password support
- Profile management

### 📱 QR Code Generation
- Generate QR codes for shortened URLs
- View QR codes through a dedicated modal
- Easily share shortened links through QR codes

### 📦 Bulk URL Shortening
- Shorten multiple URLs
- Manage multiple links efficiently
- Dedicated bulk shortening interface

### 🏷️ UTM Builder
- Create URLs with UTM parameters
- Add campaign tracking information
- Generate trackable links for marketing and analytics

### ⚡ Performance
- Redis integration for caching
- Optimized URL mapping and retrieval
- Efficient backend request handling

### 📱 Progressive Web App
- Responsive user interface
- PWA support
- Installable application experience
- Mobile-friendly design

### 🎨 User Interface
- Modern React-based frontend
- Responsive dashboard
- Landing page
- Login and registration pages
- Profile page
- Reusable modal components
- Toast notifications

---

## 🛠️ Tech Stack

### Backend
- Java
- Spring Boot
- Spring Security
- Spring Data MongoDB
- Redis
- JWT
- Maven
- Lombok

### Frontend
- React
- JavaScript
- Vite
- React Router
- Axios
- QRCode React
- Vite PWA Plugin

### Deployment & Tools
- Docker
- Render
- Vercel
- Maven Wrapper

---

## 🏗️ Project Architecture

The project is divided into two main parts:

```text
NotThatShort-URL-Shortener/
│
├── src/
│   └── main/
│       ├── java/
│       │   └── com/testing/springpractice/urlshortener/
│       │       ├── Configuration/
│       │       ├── Controller/
│       │       ├── CustomExceptions/
│       │       ├── DataTransferObjects/
│       │       ├── Models/
│       │       ├── Repository/
│       │       ├── Service/
│       │       └── UrlShortenerApplication.java
│       │
│       └── resources/
│           └── application.properties
│
├── url-shortener-frontend/
│   ├── public/
│   ├── src/
│   │   ├── api/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── context/
│   │   └── pages/
│   ├── package.json
│   └── vite.config.js
│
├── Dockerfile
├── render.yaml
├── pom.xml
├── mvnw
├── mvnw.cmd
└── README.md
