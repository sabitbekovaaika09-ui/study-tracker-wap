# Setup and Installation

## Requirements
- Node.js (for local development)
- Docker + Docker Compose (recommended)

## Backend Environment Variables
Create file: `backend/.env`

Example:
PORT=3000
MONGO_URI=mongodb://mongo:27017/studytracker
JWT_SECRET=change_me

## Run with Docker (recommended)
From repository root:
docker compose up --build

Open:
http://localhost:8080
