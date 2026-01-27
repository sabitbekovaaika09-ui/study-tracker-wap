# API Documentation

## Authentication
- POST /api/auth/register  
Registers a new user.

- POST /api/auth/login  
Logs in a user and returns JWT token.

## Tasks
- GET /api/tasks  
Returns all tasks for the authenticated user.

- POST /api/tasks  
Creates a new task.

- PATCH /api/tasks/:id  
Updates task data or status.

- DELETE /api/tasks/:id  
Deletes a task.

## Subjects
- GET /api/subjects  
Returns all subjects.

- POST /api/subjects  
Creates a new subject.

- DELETE /api/subjects/:id  
Deletes a subject.
