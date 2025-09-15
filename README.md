# DocNow API

Backend API for **DocNow**, a new MERN stack project.  
This service provides authentication, user management, and future endpoints for DocNow features.

---

## 🚀 Tech Stack
- **Node.js** + **Express.js** (REST API)
- **MongoDB** + **Mongoose** (Database)
- **JWT** + **bcryptjs** (Authentication & Security)
- **dotenv** (Environment variables)
- **morgan** (Logging)
- **cors** (Cross-origin support)
- **nodemon** (Dev auto-restart)

---

## 📂 Project Structure
docnow-api/
│── src/
│ ├── config/ # Database connection
│ ├── controllers/ # Route controllers
│ ├── middlewares/ # Custom middlewares
│ ├── models/ # Mongoose models
│ ├── routes/ # API routes
│ ├── utils/ # Helpers
│ └── index.js # App entry point
│── .env # Environment variables
│── package.json
│── README.md


## ⚙️ Setup

### 1. Clone repository
git clone https://github.com/Belgacem-Dahmen/docnow.git
cd docnow/api


### 2. Install dependencies
npm install

### 3. Configure environment
PORT=5000
MONGO_URI=mongodb+srv://<username>:<password>@cluster0.abcde.mongodb.net/docnow
JWT_SECRET=your_jwt_secret
JWT_EXPIRES_IN=1d

### 4. Run server
## For development:

npm run dev


## For production:

npm start

### 👨‍💻 Contributing

Fork the repository

Create a feature branch (git checkout -b feature/new-feature)

Commit changes (git commit -m "feat: add new feature")

Push branch (git push origin feature/new-feature)

Open a Pull Request