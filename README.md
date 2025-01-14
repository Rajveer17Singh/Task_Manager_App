# Task Manager Application

## Introduction
The *Task Manager Application* is a comprehensive productivity tool designed to help users manage, track, and organize their tasks efficiently. Built using the *MERN stack* (MongoDB, Express.js, ReactJs, and Node.js), this application allows users to create, update, delete, and categorize tasks with ease. It also offers the ability to mark tasks as completed and ensures secure data handling and seamless user experience.

## Features
- *Add Tasks*: Create tasks with titles, descriptions, and optional categories.
- *Update Tasks*: Modify task details or update their status.
- *Delete Tasks*: Remove tasks that are no longer needed.
- *Mark as Complete*: Track task completion status.
- *Category-based Filtering*: Organize tasks based on categories (e.g., Important,Incomplete,Complete etc.).
- *Responsive Design*: Fully functional on both desktop and mobile devices.
- *Authentication*: Users can sign up, log in, and manage their tasks securely.

## Technologies Used
- *Frontend*: React.js
- *Backend*: Node.js with Express.js
- *Database*: MongoDB
- *Authentication*: JSON Web Tokens (JWT)
- *Styling*: Tailwind CSS
- *API Testing*: ThunderAPI (for backend API testing)

## Prerequisites
Before running the application, ensure you have the following installed:

- *Node.js* (v14+)
- *npm* (v6+)
- *MongoDB* (local instance or MongoDB Atlas)

## Installation and Setup

Follow these steps to set up and run the application on your local system:

##  Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/Rajveer17Singh/Task_Manager_App.git
```
## Install Dependencies
Install dependencies for both the client and server:

For the Backend (server):
Navigate to the backend folder and install the required dependencies:

```bash
cd backend
npm install
```

For the Frontend (client):
Navigate to the client folder and install the necessary dependencies:

```bash
cd frontend
npm install
```

## Set Up Environment Variables
In the server folder, create a .env file (if not already provided) with the following environment variables:

``` .env
PORT = 1000
DB_URL = "mongodb+srv://raj123:raj123@cluster0.7gtum.mongodb.net/TaskManagerApp"
JWT_SECRET = "rajTM"
```

## Start the Application
Now you can start both the backend and frontend servers.

### Start the Backend:
Navigate to the root of the server directory and run:

```bash
cd backend
nodemon app.js
```
This will start the backend server.

### Start the Frontend:
Next, navigate to the client directory and run:

```bash
cd frontend
npm run start
```
This will start the React frontend.

## Access the Application
Once both the backend and frontend are running:<br/>
Backend: The backend will be accessible at http://localhost:1000.<br/>
Frontend: The frontend will be accessible at http://localhost:3000.<br/>
You can now open your browser and start using the Task Manager Application.<br/> <hr/>

#### Signup Page
![Signup Page](https://github.com/Raajveer-Singh/Task_Manager_App/blob/master/frontend/Screenshot%202024-11-29%20163831.png)
<br/> <hr/>

#### Login Page
![Login Page](https://github.com/Raajveer-Singh/Task_Manager_App/blob/master/frontend/Screenshot%202024-11-29%20163901.png)
<br/> <hr/>

#### Update Functionality
![Update Functionality](https://github.com/Raajveer-Singh/Task_Manager_App/blob/master/frontend/Screenshot%202024-11-29%20164034.png)
<br/> <hr/>

#### Main Page
![Main Page](https://github.com/Raajveer-Singh/Task_Manager_App/blob/master/frontend/Screenshot%202024-11-29%20164216.png)
<br/> <hr/>



