# 🔐 URL Shortener with Authentication

A full-stack URL Shortener application that not only generates short links from long URLs but also includes secure user authentication to manage and track personal shortened URLs.

---

## 🛠 Tech Stack

### 🌐 Frontend
- **React.js** – For building the user interface
- **Vite** – Fast development and optimized bundling
- **Axios** – For making HTTP requests
- **HTML/CSS** – For page structure and styling

### ⚙️ Backend
- **Node.js** – JavaScript runtime for server logic
- **Express.js** – Framework for building API routes
- **MongoDB** – NoSQL database for storing user data and URL mappings
- **Mongoose** – MongoDB object modeling
- **dotenv** – For environment variable management

### 🔐 Authentication
- **JWT (JSON Web Token)** – For user session management
- **bcrypt.js** – For password hashing
- **Express middleware** – To protect routes and validate tokens

---

## 🚀 What It Does

- Allows users to register and log in securely
- Authenticated users can:
  - Create short URLs from long ones
  - View and manage their personal list of URLs
- Stores all user-specific URL data in MongoDB
- Automatically redirects shortened URLs to the original long link
- Ensures only authorized users can access and manage their links
