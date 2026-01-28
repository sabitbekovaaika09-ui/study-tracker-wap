# Study Tracker – Web Application Programming (WAP)

**Student:** Sabitbekova Aikumis  
**Course:** Web Application Programming (APP1)  
**Project type:** Web application (backend-focused)

---

## 1. Project Overview

Study Tracker is a web application project developed as part of the Web Application Programming course.
The goal of the project is to demonstrate correct usage of modern web technologies, backend architecture,
and development best practices.

The current implementation focuses mainly on the backend part of the application.

---

## 2. Main Features

- Express.js backend written in TypeScript
- REST API structure
- Basic test endpoint confirming server availability
- Project structure ready for extension
- Frontend and Docker structure prepared

---

## 3. Technology Stack

- Frontend: React
- Backend: Node.js + Express.js (TypeScript)
- Database: MongoDB
- Tools: Docker, npm
- Version control: GitHub

---

## 4. Architecture

The application follows a client–server architecture:

- `frontend/` – React frontend
- `backend/` – Express backend
- `docs/` – project documentation
- REST communication between frontend and backend

---

## 5. Installation and Running

### Backend

```bash
cd backend
npm install
npx ts-node-dev --respawn --transpile-only src/index.ts
http://localhost:4000
http://localhost:4000
