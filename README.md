# 🎶 Full-Stack Spotify 2.0 ✨

A full-stack real-time music streaming application built with modern web technologies. It includes a powerful admin dashboard, integrated chat, user activity monitoring, and analytics—all synced in real time.

## 🚀 Features

- 🎸 Listen to music, skip to next/previous songs
- 🔈 Control volume using an interactive slider
- 🎧 Admin dashboard to manage albums and songs
- 💬 Real-time chat application integrated into the UI
- 👨🏼‍💼 Track user online/offline status
- 👀 See what others are currently listening to in real-time
- 📊 Aggregated listening and usage data on an analytics page
- ☁️ Cloudinary integration for media uploads
- 🔐 Authentication via Clerk
- ⚡️ Built with performance and scalability in mind

---

## 🛠 Tech Stack

**Frontend:**
- Vite + React
- Clerk for Authentication
- TailwindCSS for Styling

**Backend:**
- Node.js + Express
- MongoDB with Mongoose
- WebSockets (for real-time updates)
- Cloudinary for file storage
- Clerk for secure authentication

---

## 📦 Getting Started

### Prerequisites

- Node.js ≥ v18
- MongoDB Atlas or local MongoDB instance
- Cloudinary account
- Clerk account

---

### 🔧 Environment Setup

#### Backend `.env`

Create a `.env` file inside the `backend/` folder and fill in the following:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
ADMIN_EMAIL=admin@example.com
NODE_ENV=development

CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name

CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

```

#### frontend `.env.local`

Create a `.env.local` file inside the `frontend/` folder and fill in the following:

```env

VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key

```

## 📊 Screenshots

![Spotify-2 0](https://github.com/user-attachments/assets/a6c63279-2e80-466d-8df0-323642f8fd29)
![Spotify-Adnan](https://github.com/user-attachments/assets/39031a0d-b8e3-48aa-b67e-5c3f72dc6847)
![Spotify](https://github.com/user-attachments/assets/5a65c334-0b20-40c9-87b3-df9e78ce81ee)



