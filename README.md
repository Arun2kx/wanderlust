# 🌍 Wanderlust - Hotel Rental System

Wanderlust is a full-stack web application inspired by Airbnb. It allows users to create, and manage property listings for rental stays.

## 🚀 Features

- 🔐 User Authentication (Register/Login/Logout)
- 📍 Create, Edit, and Delete Listings
- 🖼️ Upload and manage listing images using Cloudinary
- ⭐ Flash messages for user feedback
- 🗺️ Integrated Google Maps API for location autocomplete
- 🎨 Beautiful UI built with Bootstrap

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, Bootstrap, EJS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB Atlas with Mongoose
- **Cloud Services**: Cloudinary for image hosting
- **Authentication**: Passport.js with session handling



## 🧑‍💻 Getting Started

1. **Clone the repo:**
   ```bash
  

2.**Install dependecies**:
npm install

3.**.env file**:
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_KEY=your_api_key
CLOUDINARY_SECRET=your_api_secret
DB_URL=your_mongo_db_connection_string
SECRET=session_secret_key

4.**Run the development server**:
node app.js


5.**Visit http://localhost:3000 in your browser**.

🔐 Authentication Flow
Passwords hashed using bcrypt

Session-based login/logout with express-session and passport-local


6.**FOLDER STRUCTURE**
wanderlust/
├── models/
├── public/
├── routes/
├── views/
├── utils/
├── app.js
└── README.md




