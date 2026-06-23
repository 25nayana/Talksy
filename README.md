# Talksy💬

A real-time one-to-one chat application built with React and Socket.IO. Connectify enables users to register, customize their avatars, and communicate instantly through a modern and responsive chat interface.

## 🚀 Features

* 🔐 User Authentication (Sign Up / Sign In)
* 🎭 Avatar Selection using Multiavatar API
* ⚡ Real-Time Messaging with Socket.IO
* 😀 Emoji Picker Integration
* 👥 Contacts Sidebar for Easy Navigation
* 📱 Responsive and Mobile-Friendly Design
* 🔄 Instant Message Updates Without Page Refresh

---

## 🛠️ Tech Stack

### Frontend

* React.js
* React Router DOM
* Axios
* Socket.IO Client
* React Toastify
* React Icons
* Emoji Picker React

### Backend

* Node.js
* Express.js
* MongoDB
* Socket.IO

---

## 📂 Project Structure

```text
src/
├── App.js
├── components/
│   ├── SignUp.js
│   ├── SignIn.js
│   ├── SetAvatar.js
│   ├── Chat.js
│   ├── Contacts.js
│   ├── ChatContainer.js
│   ├── ChatInput.js
│   ├── Logout.js
│   └── Welcome.js
└── utils/
    └── ApiRoutes.js
```

---

## 🔄 Application Workflow

1. User Registration
2. User Login
3. Avatar Selection
4. Contact Selection
5. Real-Time Messaging

Messages are stored in the database and delivered instantly using Socket.IO.

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/25nayana/Connectify.git
cd Connectify
```

### Install Dependencies

```bash
npm install
```

### Configure Backend URL

Update the backend host in:

```text
src/utils/ApiRoutes.js
```

Example:

```javascript
export const host = "http://localhost:5000";
```

### Run Development Server

```bash
npm start
```

Application runs at:

```text
http://localhost:3000
```

---

## 🏗️ Production Build

```bash
npm run build
```

---

## 🌟 Future Enhancements

* Group Chats
* Online/Offline Status
* Message Notifications
* File Sharing
* Voice Messages
* Video Calling
* End-to-End Encryption


* React Component Architecture
* Client-Side Routing
* REST API Integration
* State Management
* Real-Time Communication with Socket.IO
* Authentication Flow Implementation
* Responsive UI Development
