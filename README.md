# 🌍 Wanderlust - Hotel Rental System

Wanderlust is a full-stack web application inspired by Airbnb. It allows users to create, explore, and manage property listings for rental stays. The platform provides a seamless experience for both property owners and users looking for accommodations.

---

## 🚀 Features

* 🔐 User Authentication (Register, Login, Logout)
* 🏠 Create, Edit, and Delete Property Listings
* 🖼️ Image Upload and Management using Cloudinary
* ⭐ Flash Messages for Real-time User Feedback
* 🗺️ Location Autocomplete with Google Maps API
* 🎨 Responsive UI built with Bootstrap

---

## 🛠️ Tech Stack

**Frontend:**

* HTML
* CSS
* Bootstrap
* EJS

**Backend:**

* Node.js
* Express.js

**Database:**

* MongoDB Atlas
* Mongoose

**Cloud & Services:**

* Cloudinary (Image Hosting)

**Authentication:**

* Passport.js
* Express-session

---

## 📦 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Arun2kx/wanderlust.git
cd wanderlust
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the root directory and add:

```env
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_KEY=your_api_key
CLOUDINARY_SECRET=your_api_secret
DB_URL=your_mongo_db_connection_string
SECRET=session_secret_key
```

### 4. Run the Application

```bash
node app.js
```

### 5. Open in Browser

Visit: http://localhost:3000

---

## 🔐 Authentication Flow

* Passwords are securely hashed using bcrypt
* Session-based authentication using Passport.js
* Persistent login using express-session

---

## 📁 Folder Structure

```
wanderlust/
├── models/        # Database schemas
├── routes/        # Application routes
├── views/         # EJS templates
├── public/        # Static files (CSS, JS, images)
├── utils/         # Utility functions
├── app.js         # Main server file
└── README.md
```


## 📌 Future Improvements

* Add booking system with payment integration
* Implement user reviews and ratings
* Improve UI/UX with modern design frameworks
* Add search and filtering functionality

---

## 📄 License

This project is open-source and available under the MIT License.

---
