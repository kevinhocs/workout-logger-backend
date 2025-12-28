# Gym Tracker API

Backend REST API for the Workout Logger application.

Built with Node.js and Express, this server provides CRUD endpoints for managing workout logs and enforces server-side validation to ensure data integrity.

---

## Tech Stack
- Node.js
- Express
- RESTful JSON API

---

## Endpoints
- `GET /logs` – Retrieve all workout logs
- `POST /logs` – Create a new workout log
- `PUT /logs/:id` – Update an existing workout log
- `DELETE /logs/:id` – Delete a workout log

---

## Data Storage
Workout logs are stored in memory for simplicity.  
Data resets when the server restarts.

---

## Running Locally
```bash
npm install
node server.js

Server Runs at:
http://localhost:3000

