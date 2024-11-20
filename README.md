# Task Management System

## 📋 Project Overview

This is a full-stack Task Management System built with React for the frontend, Express for the backend, and using file-based storage. The application allows users to create, update, delete, and manage tasks with features like task status tracking, due date management, and detailed task views.

## 🚀 Features

- Create new tasks
- Edit existing tasks
- Delete tasks
- Mark tasks as complete
- View task details
- Separate views for in-progress and completed tasks
- Responsive design with Tailwind CSS
- Error handling and loading states

## 🛠 Technologies Used

- Frontend:
  - React
  - Tailwind CSS
  - Shadcn/UI components
  - React Icons

- Backend:
  - Express.js
  - File-based JSON storage
  - UUID for unique identifiers

## 📦 Prerequisites

- Node.js (v14 or later)
- npm (v6 or later)

## 🔧 Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/task-management-system.git
cd task-management-system
```

### Setup Backend

1. Navigate to the backend directory
```bash
cd backend
```

2. Install dependencies
```bash
npm install
```

3. Create a `.env` file in the backend directory (optional, for future expansion)
```
PORT=3001
API_URL=http://localhost:3001/api
```

### Setup Frontend

1. Navigate to the frontend directory
```bash
cd ../frontend
```

2. Install dependencies
```bash
npm install
```

3. Create a `.env` file in the frontend directory
```
REACT_APP_API_URL=http://localhost:3001/api
```

## 🏃 Running the Application

### Start Backend Server

In the `backend` directory:
```bash
npm start
```
- Server will run on `http://localhost:3001`

### Start Frontend Development Server

In the `frontend` directory:
```bash
npm start
```
- Frontend will run on `http://localhost:3000`

## 🧪 Running Tests

### Backend Tests
```bash
cd backend
npm test
```

### Frontend Tests
```bash
cd frontend
npm test
```

## 🖼 Screenshots

### Main Task List View
![Main Task List](/screenshots/task-list.png)

### Create/Edit Task Form
![Task Form](/screenshots/task-form.png)

### Task Details View
![Task Details](/screenshots/task-details.png)

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

## 📞 Contact

Your Name - youremail@example.com

Project Link: [https://github.com/yourusername/task-management-system](https://github.com/yourusername/task-management-system)
