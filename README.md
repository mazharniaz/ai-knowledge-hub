# AI Knowledge Hub

AI Knowledge Hub is a full-stack GenAI + RAG based document intelligence platform.

The goal of this project is to let users upload documents, process them, and ask questions from their private knowledge base using AI.

This project is built as a portfolio-level production-style application using React, Node.js, Express, TypeScript, PostgreSQL, Prisma, MongoDB, Redis, Docker, and later Kubernetes.

## Tech Stack

### Frontend

* React.js
* TypeScript
* Redux Toolkit
* React Router
* Tailwind CSS
* Axios
* Vite

### Backend

* Node.js
* Express.js
* TypeScript
* MVC Architecture
* PostgreSQL
* Prisma ORM
* MongoDB
* Redis
* JWT Authentication

### DevOps

* Docker
* Docker Compose
* Kubernetes later

## Project Structure

```txt
ai-knowledge-hub/
│
├── backend/
│   ├── src/
│   ├── package.json
│   ├── tsconfig.json
│   ├── .env
│   └── .env.example
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   ├── vite.config.ts
│   └── tsconfig.json
│
├── docker/
│
├── README.md
└── .gitignore
```

## Main Features Planned

* User authentication
* Role based access
* Document upload
* PDF/text extraction
* Document chunking
* Embedding generation
* Vector search
* RAG based AI chatbot
* Chat history
* Admin dashboard
* Redis queue for background processing
* Dockerized services
* Kubernetes deployment setup

## Backend Setup

```bash
cd backend
npm install
```

Create `.env` file inside `backend/`:

```env
PORT=5000
NODE_ENV=development
DATABASE_URL="postgresql://username:password@localhost:5432/ai_knowledge_hub"
JWT_SECRET="your_jwt_secret"
```

Run backend:

```bash
npm run dev
```

## Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

## Development Flow

Frontend runs on:

```txt
http://localhost:5173
```

Backend runs on:

```txt
http://localhost:5000
```

## Current Status

Project setup phase.

Completed:

* Monorepo folder structure
* Backend base setup
* Frontend base setup
* TypeScript setup
* Tailwind setup

Next steps:

* Backend Express server setup
* API route structure
* Frontend routing
* Auth module
* PostgreSQL + Prisma setup
