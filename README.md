# student-grade-book
Student Gradebook Web App
This is a simple yet functional Student Gradebook web application built using the MERN stack (MongoDB, Express, React, Node.js). The app helps manage student information, track grades, attendance, and more. It has separate interfaces for students and admins.

 Features
 Role Selection Page: Choose whether you're logging in as a student or admin.

 Login Pages: Secure login for both students and administrators.

 Student Dashboard:

View personal details, subjects, marks, grade, CGPA, and attendance.

 Admin Dashboard:

View all students.

Filter by class.

Edit student data (marks, attendance, etc).

 MongoDB Integration: All student data is stored in MongoDB for fast retrieval and updates.

 Tech Stack
Frontend: React, Tailwind CSS

Backend: Node.js, Express.js

Database: MongoDB with Mongoose

Others: Axios, React Router

 Pages Overview
/: Welcome page

/select-role: Choose between student or admin

/student-login: Student login form

/admin-login: Admin login form

/student-dashboard: Shows student details, marks, CGPA, grade, and attendance

/admin-dashboard: Admin portal to view/edit student data and apply class filters

 How to Run This Project Locally
1. Clone the Repository

git clone https://github.com/yourusername/student-gradebook.git
cd student-gradebook

3. Backend Setup

cd backend
npm install
npm start
Make sure MongoDB is running locally or update the connection string in config/db.js.

4. Frontend Setup

cd ../frontend
npm install
npm start
App will run at: http://localhost:3000

 Folder Structure

student-gradebook/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── server.js
├── frontend/
│   ├── components/
│   ├── pages/
│   └── App.js









