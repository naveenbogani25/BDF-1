# Lab 1: Node.js and Express server
Bogani Naveen Kumar · S-15

**Live link:** https://bdf-1-md87.onrender.com

## How to run
1. Install dependencies:
   npm install
2. Start the server:
   npm start

**Environment variables:** Optional `PORT` (defaults to `3000` locally).

## Endpoints

| Method | Path | Description |
| :--- | :--- | :--- |
| GET | `/` | Returns welcome text (Status 200) |
| GET | `/about` | Returns JSON with student name and section (Status 200) |
| GET | `/time` | Returns current server date and time using `new Date()` (Status 200) |
| GET | `/*` | Returns a 404 Not Found message for any unknown route (Status 404) |