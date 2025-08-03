# FriendFusion

**FriendFusion** is a real-time chat application that enables users to connect, communicate, and share images instantly. Built with modern web technologies like React, Node.js, Socket.io, and MongoDB, FriendFusion provides a seamless chat experience with user authentication, image sharing, and responsive design.
<img width="1726" height="855" alt="Screenshot 2025-08-03 155217" src="https://github.com/user-attachments/assets/e8e4867f-eba1-4a24-bd52-71b891b2f10c" />
<img width="780" height="855" alt="Screenshot 2025-08-03 155259" src="https://github.com/user-attachments/assets/2463f5b0-0a9f-4749-836f-83f484bc6212" />
<img width="1581" height="915" alt="Screenshot 2025-08-03 155243" src="https://github.com/user-attachments/assets/737c5905-e54e-4d13-9593-5f383fa18897" />

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Environment Variables](#environment-variables)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Configuration](#configuration)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)

---

## Features

- 🔐 **User Authentication**: Sign up, log in, log out using JWT and secure cookies
- 💬 **Real-Time Messaging**: Instant communication powered by Socket.io
- 📸 **Image Uploads**: Upload and share profile pictures and chat images (via Cloudinary)
- ⚙️ **User Settings**: Edit profile details and manage your account
- 📱 **Responsive UI**: Mobile-friendly interface built with React and Vite
- 🔜 **Upcoming**: Video file support for chat sharing (coming soon)

---

## Tech Stack

**Frontend:**
- React
- Vite
- Zustand (State Management)
- React Router

**Backend:**
- Node.js
- Express
- Socket.io

**Database:**
- MongoDB with Mongoose

**Authentication & Security:**
- JWT (JSON Web Tokens)
- Cookie-based session handling

**Cloud Storage:**
- Cloudinary (for images and profile pictures)

---

## Getting Started

### Prerequisites

Before starting, ensure you have the following installed:

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
- [Cloudinary](https://cloudinary.com/) account

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/chatapp.git
   cd chatapp

2. **Backend setup:**
   ```bash
   cd backend
   npm install
   # Add .env file with your credentials
   npm run dev

3. **Frontend setup:**
   ```bash
   cd ../frontend
   npm install
   npm run dev

4. **Launch the app:**
   Open your browser and go to: http://localhost:5173

**Environment Variables:**
Create a .env file in the backend/ directory and configure the following:
```env
MONGODB_URI=your_mongodb_uri
PORT=5001
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
NODE_ENV=development



