# Task Manager Application

## Introduction
The **Task Manager Application** is a comprehensive productivity tool designed to help users manage, track, and organize their tasks efficiently. Built using the **MERN stack** (MongoDB, Express.js, ReactJs, and Node.js), this application allows users to create, update, delete, and categorize tasks with ease. It also offers the ability to mark tasks as completed and ensures secure data handling and seamless user experience.

## Features
- **Add Tasks**: Create tasks with titles, descriptions, and optional categories.
- **Update Tasks**: Modify task details or update their status.
- **Delete Tasks**: Remove tasks that are no longer needed.
- **Mark as Complete**: Track task completion status.
- **Category-based Filtering**: Organize tasks based on categories (e.g., Important,Incomplete,Complete etc.).
- **Responsive Design**: Fully functional on both desktop and mobile devices.
- **Authentication**: Users can sign up, log in, and manage their tasks securely.

## Technologies Used
- **Frontend**: React.js
- **Backend**: Node.js with Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)
- **Styling**: CSS
- **API Testing**: ThunderAPI (for backend API testing)

## Prerequisites
Before running the application, ensure you have the following installed:

- **Node.js** (v14+)
- **npm** (v6+)
- **MongoDB** (local instance or MongoDB Atlas)

## Installation and Setup

Follow these steps to set up and run the application on your local system:

### 1. Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/Rajveer17Singh/Task_Manager_App.git

### 2. Install Dependencies
Install dependencies for both the client and server:

For the Backend (server):
Navigate to the server folder and install the required dependencies:

```bash
npm install

For the Frontend (client):
Navigate to the client folder and install the necessary dependencies:

```bash
cd client
npm install

### 3. Set Up Environment Variables
In the server folder, create a .env file (if not already provided) with the following environment variables:

```env
PORT = 9000
DB_URL = " mongodb+srv://raj123:raj123@cluster0.7gtum.mongodb.net/TaskManagerApp"
JWT_SECRET = "rajTM"
PORT: The port for the backend server (default: 1000).
DB_URL: MongoDB connection string for your local MongoDB instance.
JWT_SECRET: A secret key used for signing JSON Web Tokens (JWT) for secure user authentication.

### 4. Start the Application
Now you can start both the backend and frontend servers.

Start the Backend:
Navigate to the root of the server directory and run:

```bash
nodemon app.js
This will start the backend server.

Start the Frontend:
Next, navigate to the client directory and run:

bash
cd frontend
npm run start
