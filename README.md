# 📁 File Upload Backend

A backend application built with **Node.js, Express.js, MongoDB, and Cloudinary** for handling file uploads.

This project currently supports local file uploads using 'express-fileupload' and is structured to support Cloudinary-based file storage.

---

## 🚀 Features

- ✅ Express.js backend
- ✅ MongoDB database connection using Mongoose
- ✅ Cloudinary configuration
- ✅ File upload using 'express-fileupload'
- ✅ Local file storage
- ✅ REST API structure
- ✅ Environment variable support using `.env`
- ✅ Nodemon for development

---

## 🛠️ Technologies Used

- **Node.js**
- **Express.js**
- **MongoDB**
- **Mongoose**
- **Cloudinary**
- **Express File Upload**
- **Dotenv**
- **Nodemon**
- **Postman**

---

## 📂 Project Structure


FileUplode/
│
├── Config/
│   ├── cloudnary.js
│   └── database.js
│
├── controllers/
│   ├── fileUplode.js
│   └── files/
│
├── models/
│   └── File.js
│
├── routes/
│   └── FileUplode.js
│
├── .env
├── .gitignore
├── index.js
├── package.json
└── package-lock.json
