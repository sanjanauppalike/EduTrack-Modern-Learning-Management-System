# EduTrack-Modern-Learning-Management-System
EduTrack is a full-stack Learning Management System (LMS) built with Django (backend), React.js (frontend), and PostgreSQL (database). It enables online learning, course management, and student engagement through a modern, scalable platform.

## Features

- **User Authentication and Authorization**: Secure user login and role-based access control.
- **Course Creation and Enrollment**: Instructors can create courses, and students can enroll in them.
- **Content Delivery**: Upload and organize course materials such as videos, documents, and quizzes.
- **Progress Tracking and Analytics**: Monitor student progress, completion rates, and performance.
- **Discussion Forums**: Enable communication and collaboration among students and instructors.
- **User Profiles**: Personalized profiles for learners and educators.

## Technologies Used

- **Django**: A high-level Python web framework for backend development.
- **React.js**: A JavaScript library for building interactive user interfaces.
- **React Router**: For client-side routing.
- **Redux**: For state management.
- **SASS**: Used for styling components.
- **Vite**: Bundles frontend assets.
- **PostgreSQL**: Powerful relational database management system.

## Getting Started

1. **Clone the Repository**:

   ```
   git clone https://github.com/sanjanauppalike/EduTrack-Modern-Learning-Management-System/
   ```

2. **Backend Setup**:

- Navigate to the `backend` directory.
- Install dependencies:

  ```
  pip install poetry
  poetry install
  ```

- Set up the database:
  ```
  poetry run python manage.py migrate
  ```
- Run the development server:
  ```
  poetry run python manage.py runserver
  ```
  Run the tests:
  ```
  poetry run coverage run manage.py test
  poetry run coverage report
  ```

3. **Frontend Setup**:

- Navigate to the `frontend` directory.
- Install dependencies:
  ```
  yarn install
  ```
- Start the frontend application locally:
  ```
  yarn dev
  ```

4. **Access the Application**:

- Backend: http://localhost:8000
- Frontend: http://localhost:5173
