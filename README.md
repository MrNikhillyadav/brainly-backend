# 🧠 Brainly Backend

Backend service for **Brainly**, built using **Node.js**, **Express**, **TypeScript**, and **MongoDB**.  
This repository contains the API layer, database models, and core business logic powering the application.

---

## 🚀 Tech Stack

- Node.js
- Express.js
- TypeScript
- MongoDB
- Mongoose
- dotenv

---

## 📁 Project Structure

```bash
brainly-backend/
├── src/
│   ├── controllers/     # Request handlers
│   ├── routes/          # API routes
│   ├── models/          # Mongoose schemas
│   ├── middlewares/     # Custom middlewares
│   ├── config/          # DB & app configuration
│   ├── utils/           # Helper functions
│   └── index.ts         # App entry point
├── .env.example
├── tsconfig.json
├── package.json
└── README.md
```

## ⚙️ Setup & Installation
1. Clone the repository
```git clone https://github.com/<your-username>/brainly-backend.git```
```cd brainly-backend```

2. Install dependencies
```npm install```

3. Environment Variables

Create a .env file in the root directory:

PORT=5000
MONGO_URI=your_mongodb_connection_string


You can refer to .env.example for required variables.
### ▶️ Running the Server
- Development
```npm run dev```

- Production
```npm run build```
```npm start```


- Server runs on:

```http://localhost:5000```

### 📡 API Features

RESTful API architecture

MongoDB integration using Mongoose

Centralized error handling

Modular and scalable folder structure

Type-safe codebase with TypeScript

### 🧪 Scripts
npm run dev       # Start server in development mode
npm run build     # Compile TypeScript
npm start         # Start production server

### 🔒 Future Improvements

Authentication & Authorization (JWT)

Input validation (Zod / Joi)

API documentation (Swagger)

Rate limiting & security enhancements

Unit & integration testing

### 🤝 Contributing

Contributions are welcome!
Feel free to open issues or submit pull requests.

📄 License

This project is licensed under the MIT License.
