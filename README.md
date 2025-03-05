# Student-management-backend


## Overview
This is the backend of the Student Management Mobile application, responsible for handling user authentication, student data management, attendance tracking, and performance monitoring.

## Features
- User authentication (JWT/Firebase Auth)
- CRUD operations for student profiles
- Attendance tracking
- Grade and performance management
- API endpoints for frontend integration

## Technologies Used
- Node.js
- Express.js
- MongoDB with Mongoose
- Firebase Authentication
- JWT for authentication
- Nodemailer for email notifications

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/student-management-mobile-backend.git
   ```
2. Navigate to the project directory:
   ```sh
   cd student-management-mobile-backend
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Set up environment variables in a `.env` file:
   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   FIREBASE_CONFIG=your_firebase_config
   ```
5. Start the backend server:
   ```sh
   npm start
   ```



## Contribution
1. Fork the repository.
2. Create a feature branch.
3. Commit changes and push.
4. Open a pull request.

## License
This project is licensed under the MIT License.

