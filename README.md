# Hostel Management Application
## Overview
Welcome to the Hostel Management Application! This application is developed using the MERN stack (MongoDB, Express.js, React, Node.js) with Redux for state management. It is designed to manage student details, attendance, and user access control for hostel administration.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/hostel-management-app.git 
2. **Install dependencies:**
    ```bash
    npm install
    cd frontend && npm install

3 **Configure the environment variables:**

Create a .env file in the root of your project and set the following variables:
    ```bash

    NODE_ENV = development
    PORT = 5000
    MONGO_URI = [Your MongoDB connection URI]
    JWT_SECRET = [Your JWT secret key]

## Features
### Register/Login Screens
- Users can register for an account or log in using existing credentials.

### Student Details
- View a list of registered students.
- Add new students to the database.
- Edit or delete existing student details.
### Update Student Whereabouts
- Admins can update the current location or status of students.
### Attendance Management
- Record daily attendance for students.
- Display attendance details.
- Download attendance records as a CSV file.
<!-- - Delete attendance records for the previous N days. -->
### User Control
- View a list of users with their roles.
- Admins can edit user roles (admin status).
### Data Security
- Data access and control are restricted to admins only.
- JWT authentication ensures secure access to the application.

    

