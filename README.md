# IT Asset Management System (Part 1 Sample Project)

A complete full-stack project built with **React.js**, **Node.js + Express**, and **MySQL**, designed for LinkedIn series: **"Building Real-World Applications — From Development to Deployment"**.

## Project Structure
- `database.sql`: Normalized MySQL schema for departments, users, assets, and maintenance logs.
- `backend/`: Node.js & Express REST API server with connection pooling (`mysql2`).
- `frontend/`: React.js dashboard interface with Tailwind CSS styling and instant search filtering.

## Quick Start
1. Run `database.sql` in your MySQL server.
2. Setup Backend:
   ```bash
   cd backend
   npm install
   npm start
   ```
3. Setup Frontend:
   ```bash
   cd frontend
   npm install
   npm run dev
   ```
