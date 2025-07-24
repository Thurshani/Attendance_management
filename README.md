# Employee Attendance Management System

A full-stack web application to manage employee attendance, including employee registration, login, attendance check-in/check-out, and admin dashboard.

---

## Features

- Employee registration and login with JWT authentication
- Secure attendance check-in and check-out functionality
- Admin panel to view attendance logs of all employees
- Built using the MERN stack (MongoDB, Express, React, Node.js)
- Environment configuration using `.env` for sensitive info

---

## Tech Stack

- **Frontend:** React, Tailwind CSS (or your chosen CSS framework)
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (local or Atlas)
- **Authentication:** JWT (JSON Web Tokens)
- **Other:** dotenv for environment variables, cors for cross-origin requests

---

## Getting Started

### Prerequisites

- Node.js and npm installed
- MongoDB installed locally or use MongoDB Atlas
- Git installed (for cloning and version control)

### Installation

1. Clone the repository:
   
     git clone 
     cd attandance-management/attendance/server

2.Install backend dependencies:
     npm install

3.Create a .env file in the server folder with the following variables:
     PORT=5000
     MONGO_URI=mongodb://localhost:27017/employee_attendance
     JWT_SECRET=your_jwt_secret_key_here

4.Start the backend server:  
      npm run dev
