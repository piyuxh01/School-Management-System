# School Management System

## Overview
The **School Management System** is a full-stack web application built using the **MERN stack (MongoDB, Express.js, React.js, Node.js)**. It streamlines school administration by providing efficient management of students, teachers, attendance, and grading.

## Features
- **User Authentication & Authorization** – Secure login and role-based access control (RBAC) using **JWT & bcrypt**.
- **Student & Teacher Management** – Create, update, and manage profiles efficiently.
- **Attendance Tracking** – Record and monitor student attendance.
- **Grading & Performance Analysis** – Assign and analyze student grades.
- **RESTful API Development** – Efficient data handling with **Express.js & MongoDB**.
- **State Management** – Integrated **Redux** for seamless data flow.
- **Responsive UI** – Built with **React.js**, optimized for different devices.
- **Deployment & Scalability** – Hosted on **Vercel** with **CI/CD** for smooth updates.

## Tech Stack
- **Frontend**: React.js, Redux, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT, bcrypt
- **Deployment**: Vercel, CI/CD

## Installation
### Prerequisites
Ensure you have the following installed:
- Node.js
- MongoDB

### Steps to Run Locally
1. **Clone the Repository**
   ```sh
   git clone https://github.com/piyuxh01/school-management.git
   cd school-management
   ```
2. **Install Dependencies**
   ```sh
   npm install
   cd client && npm install
   ```
3. **Configure Environment Variables**
   - Create a `.env` file in the root and add:
   ```sh
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   ```
4. **Start the Backend & Frontend**
   ```sh
   npm run dev
   ```

## API Endpoints
| Endpoint              | Method | Description                  |
|----------------------|--------|------------------------------|
| `/api/auth/login`   | POST   | User authentication          |
| `/api/users`        | GET    | Fetch all users              |
| `/api/students`     | GET    | Retrieve student records     |
| `/api/attendance`   | POST   | Record student attendance    |
| `/api/grades`       | POST   | Assign student grades        |

## Contributing
Feel free to fork this repository and submit pull requests to enhance the project.

## License
This project is open-source and available under the **MIT License**.

## Connect
For any questions or contributions, reach out:
- GitHub: [HERE->](https://github.com/piyuxh01)

---
🚀 Built with MERN stack for efficient school management!

