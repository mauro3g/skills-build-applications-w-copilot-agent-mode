# OctoFit Tracker

A modern multi-tier fitness tracking application built with React 19, Node.js, Express, TypeScript, and MongoDB.

## Architecture

- **Frontend**: React 19 + Vite + TypeScript (Port: 5173)
- **Backend**: Node.js + Express + TypeScript (Port: 8000)
- **Database**: MongoDB (Port: 27017)

## Project Structure

```
octofit-tracker/
├── frontend/          # React 19 frontend application
│   ├── src/
│   ├── public/
│   └── package.json
└── backend/           # Express TypeScript backend API
    ├── src/
    │   └── server.ts
    ├── package.json
    └── .env
```

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- MongoDB (running on port 27017)
- npm or yarn

### Backend Setup

```bash
cd backend
npm install
npm run dev
```

The backend API will start on `http://localhost:8000`

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

The frontend will start on `http://localhost:5173`

## API Endpoints

- `GET /health` - Health check endpoint
- `GET /api` - API welcome message

## Environment Variables

### Backend (.env)

```
PORT=8000
MONGODB_URI=mongodb://localhost:27017/octofit-tracker
NODE_ENV=development
```

## Technologies Used

### Frontend
- React 19.2.6
- Vite 8.0.12
- TypeScript 6.0.2
- ESLint

### Backend
- Express 4.18.2
- Mongoose 8.0.3
- TypeScript 5.3.3
- tsx (for development)
- cors & dotenv

## Development

- Backend runs on port **8000**
- Frontend runs on port **5173**
- MongoDB runs on port **27017**
