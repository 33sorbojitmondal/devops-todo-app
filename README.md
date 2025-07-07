# DevOps Todo App

A full-stack todo application built with React, Node.js, and MongoDB, designed to demonstrate DevOps practices including containerization, CI/CD, and deployment.

## 🏗️ Project Structure

```
devops-todo-app/
├── frontend/          # React application
├── backend/           # Node.js/Express API
├── README.md         # This file
└── (coming soon)     # Docker, CI/CD, deployment configs
```

## 🚀 Quick Start

### Prerequisites
- Node.js (v14 or higher)
- MongoDB (local or Atlas)
- npm or yarn

### Backend Setup
```bash
cd backend
npm install
npm start
```
The backend will run on `http://localhost:5000`

### Frontend Setup
```bash
cd frontend
npm install
npm start
```
The frontend will run on `http://localhost:3000`

## 📋 Features

- ✅ Create, read, update, delete todos
- ✅ Mark todos as complete/incomplete
- ✅ Real-time updates
- ✅ Responsive design
- ✅ RESTful API

## 🔧 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/todos` | Get all todos |
| POST | `/api/todos` | Create new todo |
| PUT | `/api/todos/:id` | Update todo |
| DELETE | `/api/todos/:id` | Delete todo |

## 🐳 Next Steps - DevOps Pipeline

### 1. Containerization with Docker
- Create Dockerfiles for frontend and backend
- Set up docker-compose for local development
- Build and test containers

### 2. Version Control & CI/CD
- Push code to GitHub
- Set up GitHub Actions for automated testing
- Configure deployment pipeline

### 3. Cloud Deployment
- Deploy to cloud platform (AWS, DigitalOcean, Render)
- Set up production database
- Configure environment variables

### 4. Monitoring & Logging
- Set up application monitoring
- Configure error tracking
- Implement logging

## 🛠️ Development

### Backend Development
```bash
cd backend
npm run dev  # Uses nodemon for auto-reload
```

### Frontend Development
```bash
cd frontend
npm start    # Starts development server
```

## 📝 Environment Variables

Create a `.env` file in the backend directory:
```
PORT=5000
MONGODB_URI=mongodb://localhost:27017/todo-app
```

For production, use MongoDB Atlas or your preferred cloud database.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE). 