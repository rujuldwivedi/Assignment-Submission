# Assignment Submission System

**A web application for submitting and managing assignments with intuitive features for students and instructors.**

---

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)

---

## Project Overview

The **Assignment Submission System** is designed to streamline the process of submitting, reviewing, and grading assignments. It offers students a platform to upload their assignments, while instructors can easily review submissions, provide feedback, and assign grades.

<p align="center">
  <img src="AssignmentSubmissionApp/front-end/src/assignment-gif.gif" alt="Assignment Submission GIF" />
</p>

---

## Features

- **User Authentication & Authorization**: Secure user login via JWT.
- **Assignment Submission**: Students can submit assignments and track their status.
- **Instructor Grading & Feedback**: Instructors can review submissions, provide feedback, and assign grades.
- **User Profile Management**: Manage user details and roles.

---

## Technologies Used

- **Frontend**: React.js
- **Backend**: Spring Boot (Java)
- **Database**: MySQL
- **Authentication**: JSON Web Tokens (JWT)

---

## Getting Started

To set up and run the Assignment Submission System locally, follow these steps:

1. **Clone the repository**:  
   ```
   git clone https://github.com/rujuldwivedi/Assignment-Submission-System.git
   ```

2. **Backend Setup**:  
   Ensure that Java and Spring Boot are installed. Navigate to the backend folder and configure the database connection in `application.properties`.

   ```
   cd AssignmentSubmissionApp/backend
   ```

   Then, run the Spring Boot application:

   ```
   mvn spring-boot:run
   ```

3. **Frontend Setup**:  
   Navigate to the frontend folder and install dependencies.

   ```
   cd AssignmentSubmissionApp/front-end
   npm install
   npm start
   ```

4. **Database Setup**:  
   Ensure you have MySQL running and the database configured as per `application.properties`.

---

## Usage

Once the application is running, access the platform via `http://localhost:3000`. Log in as a student or instructor to interact with the following features:

- **Students**: Submit assignments and view status updates.
- **Instructors**: Review submissions, assign grades, and provide feedback.

---

## Contributing

Contributions are welcome! If you’d like to add features, fix bugs, or improve the documentation, feel free to open an issue or submit a pull request.

---

## Acknowledgments

Special thanks to [Trevor Page](https://www.youtube.com/watch?v=xuOuzLWQy3A&list=PL2OrQJM8zmZ2-O_rM2Ju9zYMbY8Ta-8I4) for his invaluable tutorials.
