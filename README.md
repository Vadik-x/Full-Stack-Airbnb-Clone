🏠 Airbnb Clone – Full Stack Web Application

A full-stack Airbnb-style web application built using Node.js, Express, MongoDB, and EJS, featuring user authentication, property listings, reviews, image uploads, and session management.
The project follows MVC architecture and focuses on clean backend structure, validation, and real-world deployment.

🚀 Live Demo

Hosted on Render
🔗 https://airbnb-clone-kcgc.onrender.com/

🛠 Tech Stack
Backend

Node.js (v22.18.0)
Express.js
MongoDB & Mongoose
Passport.js (Local Strategy)
Express Session + MongoDB Store
Joi (Schema validation)

Frontend

EJS (Server-side rendering)
CSS
EJS Partials (Reusable components)

Media & Storage

Cloudinary (Image upload & storage)
Multer (File handling)

Deployment
Render
dotenv for environment configuration

✨ Features

🔐 User Authentication (Register / Login / Logout)
🏡 Create, Edit & Delete Property Listings
🖼 Image Upload with File Size Validation
⭐ Review & Rating System
🗺 Map Integration for Listing Location
💬 Flash Messages for UX feedback
🧠 Robust Error Handling
🧱 MVC Architecture
🔒 Protected Routes & Middleware

AIRBNB-PROJECT
├── controllers
│   ├── listing.js
│   ├── reviews.js
│   └── user.js
├── models
│   ├── listing.js
│   ├── review.js
│   └── user.js
├── routes
│   ├── listing.js
│   ├── reviews.js
│   └── user.js
├── utils
│   ├── expressError.js
│   └── wrapAsync.js
├── public
│   ├── css
│   ├── images
│   └── js
├── views
│   ├── pages
│   └── partials
├── middleware.js
├── cloudConfig.js
├── schema.js
├── app.js
└── package.json

🔑 Environment Variables

Create a .env file in the root directory:
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_KEY=your_key
CLOUDINARY_SECRET=your_secret
DB_URL=your_mongodb_url
SESSION_SECRET=your_session_secret

⚙️ Installation & Setup

# Clone the repository
git clone https://github.com/your-username/airbnb-project.git

# Navigate into the project
cd airbnb-project

# Install dependencies
npm install

# Start the server
nodemon app.js

Server runs on:
http://localhost:3000

🧠 Key Learnings & Highlights

Implemented secure authentication using Passport & sessions
Designed RESTful routes with proper validation
Used Cloudinary for scalable image handling
Applied MVC architecture for clean separation of concerns
Built reusable middleware for authorization & error handling
Deployed a production-ready app on Render

👤 Author

Vadik Malik
Full Stack Developer
Focused on building real-world, scalable backend systems.

📌 Future Improvements

Booking & availability system
Payment integration
Search & advanced filters
Pagination & performance optimization
