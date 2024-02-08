# Interview Task - Next.js To-Do List with Flask Backend and SQLAlchemy

## Overview
This repository contains an interview task aimed at assessing skills in Docker, Next.js, Flask, and SQLAlchemy development. The task involves completing Docker setup for both frontend and backend, developing a simple to-do list application using Next.js and Flask, and integrating SQLAlchemy for a SQLite database connection.

## Task Description

### 1. Dockerize the Frontend (Next.js)
- Complete the Dockerfile in the `frontend/` directory to ensure the Next.js app can be built and run in a Docker container.

### 2. Dockerize the Backend (Flask)
- Complete the Dockerfile in the `backend/` directory for the Flask app to be containerized.

### 3. Develop a Simple To-Do List Application
- **Frontend (Next.js):**
  - Create an interface for task management (add, view, delete).
  - Implement communication with the backend API.
- **Backend (Flask):**
  - Develop a REST API for CRUD operations on tasks.
  - Use SQLAlchemy to connect to a SQLite database for persisting tasks.

### 4. Integrate SQLAlchemy with SQLite
- Set up SQLAlchemy in the Flask application for database operations.
- Ensure tasks are stored and retrieved from a SQLite database.

## Getting Started

### Clone the Repository
```bash
git clone https://github.com/your-repository/interview-task.git
cd interview-task