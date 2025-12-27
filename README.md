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
StayEase/
├── app.js
├── cloudConfig.js
├── middleware.js
├── schema.js
├── controllers/
│   ├── listings.js
│   ├── reviews.js
│   └── users.js
├── models/
│   ├── listing.js
│   ├── review.js
│   └── user.js
├── routes/
│   ├── listing.js
│   ├── review.js
│   └── user.js
├── views/
│   ├── layouts/
│   ├── listings/
│   ├── users/
│   └── error.ejs
├── public/
│   ├── css/
│   └── js/
├── utils/
│   ├── ExpressError.js
│   └── wrapAsync.js
├── .gitignore
├── package.json
└── README.md
