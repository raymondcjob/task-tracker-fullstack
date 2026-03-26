# Service Request / Task Management System

Full-stack application simulating a service request management system used by IT service providers to track, update, and maintain client tasks.

## Overview

This project demonstrates the development of a structured web application with RESTful API design, JSON-based communication, and persistent data storage. It reflects real-world scenarios where systems are used to manage workflows and maintain operational data.

## Features

- Create, update, and delete tasks (CRUD operations)
- Toggle task completion status
- RESTful API with JSON request/response handling
- Persistent storage using PostgreSQL
- Responsive frontend with real-time updates

## Tech Stack

### Backend
- C#
- ASP.NET Core Web API (.NET 10)
- Entity Framework Core
- PostgreSQL

### Frontend
- React
- Vite
- Axios

## API Endpoints

| Method | Endpoint       | Description     |
|--------|---------------|-----------------|
| GET    | /api/task      | Get all tasks   |
| GET    | /api/task/{id} | Get task by ID  |
| POST   | /api/task      | Create new task |
| PUT    | /api/task/{id} | Update task     |
| DELETE | /api/task/{id} | Delete task     |

## Technical Skills

This project demonstrates:

- Writing, modifying, and testing software code
- Developing RESTful APIs using JSON-based communication
- Structuring and maintaining application logic
- Managing data flow between frontend and backend systems
- Implementing features commonly used in business and IT service applications

## Testing & Validation

- API endpoints tested using Postman
- Input validation implemented for data integrity
- Error handling for invalid requests

## Getting Started

### Run Backend
cd TaskApi  
dotnet run  

### Run Frontend
cd task-ui  
npm install  
npm run dev  

## Screenshot

![Task Tracker Screenshot](screenshots/app.png)

## Future Improvements

- Add authentication and authorization
- Implement pagination and filtering
- Enhance logging and monitoring