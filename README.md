
---

# MERN Auth Backend (TypeScript + JWT + MVC)

A secure, scalable backend built with **Node.js**, **Express**, **TypeScript**, and **MongoDB**, implementing **JWT-based authentication** for user signup and login. The project follows the **MVC architecture** and includes robust **input validation** and middleware handling.

---

## 🚀 Features

- 🔐 Signup & Login using **JWT** authentication
- ✅ Request validation with middleware
- 📦 Clean **MVC architecture**
- 🧱 MongoDB & Mongoose for database interaction
- ⚙️ Built with **TypeScript** for type safety and maintainability
- 📁 Environment variable support
- 🔄 CORS and body-parser middleware preconfigured

---

## 🗂 Folder Structure

```

server/
├── src/
│   ├── config/         # MongoDB connection config
│   ├── controllers/    # Business logic (e.g., authController)
│   ├── middleware/     # JWT auth, error handlers, validation
│   ├── models/         # Mongoose models
│   ├── routes/         # Express routes (e.g., /api/auth)
│   ├── utils/          # Helper functions
│   ├── validators/     # Request validation (e.g., signup schema)
│   ├── app.ts          # Express app setup
│   └── server.ts       # Entry point

````

---

## 🛠️ Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/your-username/mern-auth-backend.git
cd mern-auth-backend
````

### 2. Install dependencies

```bash
npm install
```

### 3. Setup environment variables

Create a `.env` file in the `server` directory and add the following:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

### 4. Run the server

```bash
npm run dev
```

The server will start at `http://localhost:5000`.

---

## 📬 API Endpoints

| Method | Endpoint           | Description                       |
| ------ | ------------------ | --------------------------------- |
| POST   | `/api/auth/signup` | Register a new user               |
| POST   | `/api/auth/login`  | Login with credentials            |

---

## 🧪 Tech Stack

* **Node.js** + **Express**
* **TypeScript**
* **MongoDB** + **Mongoose**
* **JWT** for authentication
* ** Joi / custom** validation
* **dotenv** for environment config
* **CORS** for security/logging

---

## 🙌 Acknowledgements

Built as part of a MERN stack full authentication project using modern web development practices and clean architecture.

---
