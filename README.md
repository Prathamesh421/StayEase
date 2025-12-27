# 🏡 StayEase
StayEase is a full-stack web application for listing and reviewing rental properties.  
The project focuses on clean backend architecture, secure authentication, and scalable session management.

## ✨ Features
- User authentication and authorization using Passport.js
- Create, edit, and delete property listings
- Review system with ownership checks
- Image uploads using Cloudinary
- Session-based authentication with MongoDB session store
- Server-side validation using Joi
- Flash messages for user feedback
- MVC architecture for clean and maintainable code

## 🛠️ Tech Stack
### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
### Authentication & Security
- Passport.js (Local Strategy)
- express-session
- connect-mongo
### Frontend
- EJS
- Bootstrap
### Other Tools
- Multer
- Cloudinary
- Joi
- Method-Override

## 📂 Project Structure
```text
StayEase/
├── app.js
├── cloudConfig.js
├── middleware.js
├── schema.js
├── controllers/
│ ├── listings.js
│ ├── reviews.js
│ └── users.js
├── models/
│ ├── listing.js
│ ├── review.js
│ └── user.js
├── routes/
│ ├── listing.js
│ ├── review.js
│ └── user.js
├── views/
│ ├── layouts/
│ ├── listings/
│ ├── users/
│ └── error.ejs
├── public/
│ ├── css/
│ └── js/
├── utils/
│ ├── ExpressError.js
│ └── wrapAsync.js
├── .gitignore
├── package.json
└── README.md

🚀 Run Locally
1️⃣ Clone the repository-
  git clone https://github.com/Prathamesh421/StayEase.git
  cd StayEase

2️⃣ Install dependencies-
  npm install

3️⃣ Environment Variables-
  Create a .env file in the root directory:
  
  MONGO_URL=your_mongo_url
  SESSION_SECRET=your_session_secret
  CLOUDINARY_CLOUD_NAME=your_cloud_name
  CLOUDINARY_KEY=your_api_key
  CLOUDINARY_SECRET=your_api_secret

4️⃣ Start MongoDB-
  Ensure MongoDB is running locally on your machine.

5️⃣ Start the server-
  npm start
  or (if using nodemon):
  nodemon app.js

6️⃣ Open in browser
  http://localhost:8080
