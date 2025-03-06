# Scl-Management-
# School Management MERN Application

This is a full-stack web application built with the MERN stack (MongoDB, Express.js, React.js, Node.js) designed to manage various aspects of a school's operations.

## Features

* **Student Management:**
    * Add, edit, and delete student records.
    * View student details, including personal information, attendance, and grades.
    * Search and filter students.
* **Teacher Management:**
    * Add, edit, and delete teacher records.
    * View teacher details, including contact information and assigned classes.
    * Search and filter teachers.
* **Class Management:**
    * Create, edit, and delete class records.
    * Assign teachers and students to classes.
    * View class schedules.
* **Attendance Tracking:**
    * Mark student attendance.
    * Generate attendance reports.
    * View attendance history.
* **Grade Management:**
    * Record and manage student grades.
    * Generate grade reports.
    * Calculate average grades.
* **User Authentication:**
    * Secure user login and registration.
    * Role-based access control (e.g., admin, teacher, student).
* **Responsive Design:**
    * The application is designed to be responsive and work on various devices.

## Technologies Used

* **Frontend:**
    * React.js
    * React Router
    * Axios (for API requests)
    * CSS/Styled-components/Material-UI/TailwindCSS (choose one for styling)
* **Backend:**
    * Node.js
    * Express.js
    * MongoDB (with Mongoose)
    * JSON Web Tokens (JWT) for authentication
    * bcrypt (for password hashing)
    * cors
* **Database:**
    * MongoDB

## Getting Started

1.  **Clone the repository:**

    ```bash
    git clone <repository-url>
    ```

2.  **Navigate to the backend directory:**

    ```bash
    cd <repository-name>/backend
    ```

3.  **Install backend dependencies:**

    ```bash
    npm install
    ```

4.  **Create a `.env` file in the backend directory and add your MongoDB connection string and JWT secret:**

    ```
    MONGODB_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```

5.  **Start the backend server:**

    ```bash
    npm run dev
    ```

6.  **Navigate to the frontend directory:**

    ```bash
    cd ../frontend
    ```

7.  **Install frontend dependencies:**

    ```bash
    npm install
    ```

8.  **Create a `.env.local` file in the frontend directory and add your backend API URL:**

    ```
    REACT_APP_API_URL=http://localhost:5000/api #or your deployed backend URL.
    ```

9.  **Start the frontend development server:**

    ```bash
    npm start
    ```

10. **Open your browser and navigate to `http://localhost:3000` to view the application.**

## Project Structure