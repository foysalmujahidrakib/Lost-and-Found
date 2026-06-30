# 🔍 Lost & Found Management System

A modern **MERN Stack** web application designed to help users report, search, and recover lost or found items through a secure and intuitive platform. The system enables users to publish lost or found item reports, search existing records, and connect with item owners, making the recovery process faster and more efficient.

---

## ✨ Features

* 🔐 Secure user registration and authentication
* 📦 Report lost and found items with detailed information
* 📷 Image upload support for item identification
* 🔎 Search items by title or keywords
* 📋 View detailed information for each item
* 📱 Fully responsive user interface
* ☁️ MongoDB database integration for reliable data storage
* ⚡ RESTful API built with Express.js
* 🚀 Fast frontend powered by React and Vite

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Vite
* JavaScript (ES6+)
* Tailwind CSS
* Redux

### Backend

* Node.js
* Express.js
* Mongoose
* JWT Authentication
* Bcrypt
* Multer
* Cloudinary
* Nodemailer

### Database

* MongoDB

### Deployment

* Render

---

## 📁 Project Structure

```text
LostAndFound/
├── backend/              # Express.js backend
├── src/                  # React frontend
├── public/
├── package.json
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/LostAndFound.git
cd LostAndFound
```

### 2. Install Frontend Dependencies

```bash
npm install
```

### 3. Install Backend Dependencies

```bash
cd backend
npm install
```

### 4. Configure Environment Variables

Create a `.env` file inside the `backend` directory and configure the following variables:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
EMAIL=your_email
EMAIL_PASSWORD=your_email_password
```

### 5. Start MongoDB

Ensure your MongoDB server is running before starting the backend.

### 6. Run the Backend

```bash
cd backend
npm start
```

### 7. Run the Frontend

```bash
cd ..
npm run dev
```

---

## 🌐 Live Demo

**Frontend:** https://lostandfound-frontend.onrender.com

---

## 📖 How to Use

1. Register a new account or log in.
2. Report a lost or found item by providing its details.
3. Upload an image to improve identification.
4. Search for items using keywords.
5. View complete item information.
6. Contact the owner after finding a matching item.

---

## 🚀 Future Improvements

* AI-powered matching of lost and found items
* Real-time notifications
* Chat system between users
* Interactive map integration
* Admin dashboard
* Mobile application
* Advanced filtering and sorting
* Email notifications for potential matches

---

## 🤝 Contributing

Contributions are always welcome!

1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes.
4. Push your branch.
5. Open a Pull Request.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

### **Foysal Mujahid Rakib**

Computer Science & Engineering (CSE) Student
Bangladesh University of Business and Technology (BUBT)

* GitHub: https://github.com/foysalmujahidrakib
* Email: [foysalmujahidrakib@gmail.com](mailto:foysalmujahidrakib@gmail.com)

---

⭐ If you found this project useful, consider giving it a **Star** on GitHub to support the project!
