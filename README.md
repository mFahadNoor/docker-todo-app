# Dockerized MERN Todo Application

A Dockerized version of the MERN stack todo application, based on [zaheersani/todo-mern](https://github.com/zaheersani/todo-mern/).

## Features

- Full MERN stack implementation
- Docker containerization for easy deployment
- User authentication with JWT
- CRUD operations for todo items
- Responsive design for mobile and desktop
- MongoDB database with Docker support

## Prerequisites

- Docker installed on your system
- Node.js (for development)
- npm (for development)

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/mFahadNoor/docker-todo-app.git
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Start the backend server:
```bash
node server.js
```

## Docker Deployment

To deploy using Docker:

1. Build the Docker image:
```bash
docker-compose build
```

2. Start the containers:
```bash
docker-compose up
```

## Technology Stack

- Frontend: React, Axios
- Backend: Node.js, Express.js, MongoDB, Mongoose
- Deployment: Docker

## Acknowledgments

This project is based on [zaheersani/todo-mern](https://github.com/zaheersani/todo-mern/), with modifications to support Docker containerization.
