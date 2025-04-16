
# 🌐 Social Media Web Application

A feature-rich, full-stack social media platform inspired by modern networks like Facebook, Twitter, and Signal. Built with **React.js**, **Node.js**, and **MongoDB**, this project enables seamless user interaction through posts, comments, shares, messaging, and real-time notifications.

> ⚠️ **Note:** Environment variables and secret keys have been removed for security. Please configure your own `.env` file and proxy settings in `package.json` to run locally.

---

## 🔧 Features

### ✍️ Posts, Comments & Sharing
- Create rich text or image-based posts
- Comment on any post with text or media
- Share others' posts using direct references or embeds

### 🔐 Authentication & Security
- User registration & login with **JWT-based authentication**
- Secure password hashing using **BCrypt**
- Session management without third-party auth providers

### 📢 Notifications
- Receive in-browser or email notifications on comments or shares
- Configurable notification settings per user

### 💬 Messaging *(Planned)*
- Private one-on-one chat between users *(coming soon)*

---

## 🛠️ Tech Stack

| Frontend | Backend | Database | Auth & Security | Tools |
|----------|---------|----------|------------------|-------|
| React.js | Node.js (Express) | MongoDB | JWT, BCrypt | REST API, npm |

---

## 🚀 Getting Started

### 📦 Prerequisites
- [Node.js & npm](https://nodejs.org/en/download/)
- MongoDB (local or cloud – e.g., [MongoDB Atlas](https://www.mongodb.com/cloud/atlas))

### 📁 Project Setup

```bash
# Clone the repository
git clone https://github.com/adnan-1010/social-media.git

# Navigate to the project directory
cd social-media

# Move to the client directory
cd client

# Install dependencies
npm install

# Start the development server
npm start
```

> The frontend will be available at `http://localhost:3000`

---

## ⚙️ Environment Setup

Create a `.env` file in the root of your server/client directory and add:

```env
REACT_APP_API_URL=http://localhost:5000
REACT_APP_SOME_KEY=your_key_here
```

Also, update the `"proxy"` key in `package.json` if needed.

---

## 🗃️ Folder Structure

```
social-media/
│
├── client/              # React frontend
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── utils/
│       └── App.js
│
└── server/ *(planned)*  # Backend API with Node.js and Express
```

---

## 📌 Roadmap

- [x] User authentication (JWT)
- [x] Post creation & comments
- [x] Basic share feature
- [ ] Private messaging
- [ ] Real-time notifications via WebSocket
- [ ] Profile customization

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

---

## 📫 Contact

Made with ❤️ by [Adnan](https://github.com/adnan-1010)  
Questions or feedback? Drop an issue or connect via GitHub.

---


