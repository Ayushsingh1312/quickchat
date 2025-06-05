# 💬 QuickChat – MERN Stack Real-Time Chat App with Socket.io

QuickChat is a full-stack real-time messaging application built with the **MERN stack** and **Socket.io**. It allows users to sign up, chat with others in real-time, update profiles, and share images seamlessly.

---

## 🚀 Features

- 🔐 User Authentication (Sign Up / Login)
- 🧑‍💼 Edit Profile (Name, Bio, Profile Picture)
- 💬 Real-Time Messaging with **Socket.io**
- 📷 Send & View Images in Chat
- ✅ Online/Offline User Status
- 🔔 Unseen Message Counter
- 🌙 Modern UI with responsive design
- 🔒 JWT-Based Protected Routes
- 📦 Environment-based Configuration (`.env` support)

---

## 🛠️ Tech Stack

- **Frontend**: React.js, Tailwind CSS, Axios, React Router
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose)
- **Real-time Engine**: Socket.io
- **Auth**: JWT, bcrypt
- **Image Upload**: Cloudinary

---

## ⚙️ Setup Instructions

### 🔧 Prerequisites
- Node.js & npm installed
- MongoDB (local or cloud)
- Cloudinary account (for image upload)

---

### 📦 Clone the Repository

```bash
git clone https://github.com/Ayushsingh1312/quickchat.git
cd quickchat

```

#### 🔑 Setup Environment Variables
Create .env files inside both client/ and server/ folders.

`server/.env`
<pre>
PORT=your_port_number
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
</pre>

`client/.env`
<pre>
VITE_BACKEND_URL=http://localhost:PORT
</pre>

---

 ### 📁 Install Dependencies
#### Server:
```bash
cd server
npm install
```
#### Client:
```bash
cd ../client
npm install
```
---

### ▶️ Run the App
#### Start Backend
```bash
cd server
npm start
```
#### Start Frontend
```bash
cd ../client
npm run dev
```
