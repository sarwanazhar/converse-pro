# 💬 MERN Stack Chat Application [conversepro ]

A real-time chat application built using the **MERN** stack (MongoDB, Express.js, React, Node.js) with **Socket.IO** for real-time communication. This app allows users to register, log in, create one-on-one or group chats, and exchange messages instantly.

## 🚀 Features

- 🧑‍💻 User authentication (JWT-based)
- 🔐 Secure password hashing with bcrypt
- 📦 Persistent message storage using MongoDB
- ⚡ Real-time messaging with Socket.IO
- 🧵 Private and group chat support
- 🖼️ Profile pictures using Cloudinary (or local storage)
- 🔔 Online users and typing indicators
- 📱 Responsive UI built with React + Tailwind CSS (or Bootstrap)

---

## 🛠️ Tech Stack

**Frontend:**
- React
- Axios
- React Router
- Tailwind CSS 

**Backend:**
- Node.js
- Express.js
- MongoDB + Mongoose
- Socket.IO
- JSON Web Tokens (JWT)
- bcrypt

---

## 📦 Installation

### Prerequisites
- Node.js & npm
- MongoDB (local or cloud)
- Cloudinary account (optional, for image uploads)

### Clone the repository

```bash
git clone https://github.com/sahilmd01/converse-pro.git
cd converse-pro
````

### Install server dependencies

```bash
cd backend
npm install
```

Create a `.env` file in the `backend/` folder and add:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

### Install client dependencies

```bash
cd ../frontend
npm install
```

---

## 🚀 Running the Application

### Start the backend server

```bash
cd backend
npm run dev
```

### Start the frontend client

```bash
cd frontend
npm start
```

Open your browser and navigate to `http://localhost:5173`.

---

## 📸 Screenshots

> Include some screenshots or GIFs showing the app in action:

* Login page
* Chat dashboard
* Group chat
* Typing indicator

---

## 📂 Project Structure

```
mern-chat-app/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── config/
│   └── server.js
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.js
└── README.md
```

---

## 📬 API Endpoints

### Auth

* `POST /api/user/register` – Register new user
* `POST /api/user/login` – Login user

### Chat

* `GET /api/chat/` – Get user's chats
* `POST /api/chat/` – Create new chat
* `POST /api/chat/group` – Create group chat

### Messages

* `GET /api/message/:chatId` – Get messages in a chat
* `POST /api/message/` – Send new message

---

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

---

## 📃 License

This project is licensed under the [MIT License](LICENSE).

---

## 🧑‍💻 Author

**SAHIL**
[GitHub](https://github.com/sahilmd01) • [LinkedIn](https://linkedin.com/in/codewithkinu) • [youtube](https://youtube.com/@codewithkinu)



