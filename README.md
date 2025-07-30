# Todo App

## Overview

A simple yet powerful Todo application built with modern web technologies(MERN Stack). This app allows users to create, manage, and organize their tasks efficiently with a clean and responsive interface.

You can access the application here [Live Here](https://task-app-z6t4.onrender.com)

## Technologies Used
- Backend: Node.js v12.22.12
- Database: MongoDB v4.2
- Frontend: React v17.0.2
- Build Tool: Vite v2
- Styling: Tailwind CSS v2

## Features
- Create, read, update, and delete todos
- Responsive design for all screen sizes
- Fast and lightweight thanks to Vite
- Modern UI with Tailwind CSS

## Prerequisites
Before you begin, ensure you have met the following requirements:
- Node.js v12.22.12 installed
- MongoDB v4.2 installed and running
- Git (optional) for version control

### Backend Setup

1. Clone the repo:

   ```bash
   git clone https://github.com/kipngetich-lab/week-7-assignment.git
   cd week-7-assignment
   ```

2. Install dependencies:

	```bash
	npm install && cd client && npm install && cd ..
	```

3. Create .env file in the root:

	```javascript
	PORT=5000
	MONGO_URI=mongodb://localhost:27017/task-db
	JWT_SECRET=your_jwt_secret_key
	```

4. Start the backend server:

	```bash
	npm run dev
	```

5. Navigate to client folder:

	```bash 
	cd client
	```

6. Start the frontend development server:

	```bash
	npm run dev
	```

7. Open http://localhost:3000 in your browser.

### API Endpoints

	Authentication

    POST /api/auth/register - Register a new user
    POST /api/auth/login - Login and receive JWT token

	Tasks

    POST /api/tasks/ - user adds a new task (default status: pending)
    UPDATE /api/tasks/taskId - user update task
    DELETE /api/tasks/taskId - user delete task

### How to Use

    1. Register as a user.
    2. users can view their own tasks(all,completed,pending,in progress).

### Deployment

	  1. Set environment variables on your production server or hosting platform(render)

    3. Deploy the application under one domain both frontend and backend with production MONGODB_URI, JWT_SECRET and JWT_EXPIRE.

### Contributing

	Contributions are welcome! Please fork the repo and create a pull request with your improvements.

### License

	MIT License 

### Contact
	
	For questions or support, reach me at joskipngetich07@gmail.com


