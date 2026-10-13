# To-Do List Application (React + Express + MongoDB)

Create, list, complete, and delete tasks. Backend routes validate input and use MongoDB.

## Setup
1. Install Node.js 18+ and have MongoDB running locally or create a MongoDB Atlas database.
2. Copy `.env.example` to `.env` and set `MONGODB_URI`.
3. In this folder run:
   ```bash
   npm install
   npm run dev
   ```
4. Open http://localhost:3000.

If MongoDB is unavailable, the UI displays an API error rather than silently pretending data was saved. Do not commit `.env`.
