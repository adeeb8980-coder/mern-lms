MERN Learning Management System (LMS)

Project Overview:
This project is a Full Stack Learning Management System built using the MERN stack (MongoDB, Express.js, React.js, Node.js).
It allows Admins, Instructors, and Students to manage and access online courses.

Key Features:

User registration and login (JWT authentication)
Role-based access (Admin, Instructor, Student)
Course creation, update, and deletion
Student course enrollment
Admin dashboard for managing users and courses
RESTful API integration

Installation Steps:

cd mern-lms
Setup Backend:
cd backend
npm install

Create a .env file and add:
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

Run backend:
npm run dev

Setup Frontend:
cd ../frontend
npm install

Run frontend:
npm start

Open in browser:
Frontend: http://localhost:3000

Backend: http://localhost:5000

Technologies Used:

Frontend:

React JS
React Router DOM
Axios
Bootstrap / CSS

Backend:

Node.js
Express.js
MongoDB
Mongoose

Authentication:

JWT (JSON Web Token)
Bcrypt
Dotenv

Project Structure:

Backend:

models
controllers
routes
middleware
config
server.js
.env

Frontend:

components
pages
services
routes
App.js

Future Improvements:

Payment system
Video lessons upload
Progress tracking
Notifications system