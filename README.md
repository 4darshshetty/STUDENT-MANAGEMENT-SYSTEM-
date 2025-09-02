# STUDENT MANAGEMENT SYSTEM (MERN)

A simple MERN stack app to manage students with create, read, update, and delete operations.

## Tech Stack
- Backend: Node.js, Express, Mongoose
- Frontend: React (Create React App)
- Database: MongoDB

## Prerequisites
- Node.js 16+ and npm
- MongoDB running locally (default: mongodb://localhost:27017)
- Git

## Project Structure
- Backend/: Express + Mongoose API
- Frontend/: React SPA

## Environment Variables
Backend .env example (already present):
`
PORT=8070
MONGODB_URL=mongodb://localhost:27017/student-management-system
`

## Local Setup
1. Install dependencies:
`
cd Backend && npm install
cd ../Frontend && npm install
`

2. Start servers (two terminals):
- Backend:
`
cd Backend
npm run start
`
- Frontend:
`
cd Frontend
npm start
`
- App runs on http://localhost:3000, API on http://localhost:8070.

If you see MongooseServerSelectionError: ECONNREFUSED ::1:27017, ensure MongoDB is running locally:
- Windows: Start the MongoDB service (Services app) or run mongod.

## Scripts
- Backend: 
pm run dev (nodemon), 
pm run start
- Frontend: 
pm start, 
pm run build

## Deployment
- Backend has ercel.json for serverless deployment.
- Ensure MONGODB_URL is set in the deployment environment.

## License
ISC
