
# TaskFlow - MERN Stack Task Management Application

## Project Overview
This project is an implementation of the TaskFlow test, a MERN stack task management application with authentication, task management, filtering, and administrative features.

## Features Implemented

### 1. Task List in Navbar
- Displays tasks with title, description, and status in a dropdown from the navbar
- Allows marking tasks as complete or incomplete
- Provides task editing functionality
- Implements localStorage for persistent data storage

### 2. Authentication System
- Login/Register pages before accessing the main application
- Role-based access control (admin/user)
- Protected routes that require authentication
- Persistent user sessions with localStorage

### 3. Task Filtering
- Filter tasks by completion status (All/Complete/Incomplete)
- Search functionality to filter tasks by title
- Real-time filtering as users type or select options
- Responsive design for all screen sizes

### 4. User Log Page for Admin
- Comprehensive display of user activity logs
- Shows login time, logout time, JWT token, username, role, and IP address
- Delete functionality for admin users
- Sorting and filtering capabilities

## Technologies Used
- **Frontend**: React, React Router, TailwindCSS
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Authentication**: JWT-based authentication
- **State Management**: React Context API and localStorage

## Installation & Setup

### Prerequisites
- Node.js v20.0.0 or higher
- MongoDB

### Setup Steps
1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/react-node-task-manager.git
cd react-node-task-manager
