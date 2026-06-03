# OctoFit Tracker

A modern multi-tier fitness tracking application built with React 19, Express, and MongoDB.

## Project Structure

```
octofit-tracker/
├── frontend/          # React 19 + Vite frontend application
└── backend/           # Node.js + Express + TypeScript API server
```

## Architecture

- **Frontend**: React 19 with Vite development server
  - Port: 5173
  - Framework: Vite
  - Runtime: Browser

- **Backend**: Node.js with Express and TypeScript
  - Port: 8000
  - Framework: Express.js
  - ORM: Mongoose
  - Database: MongoDB

- **Database**: MongoDB
  - Port: 27017
  - Host: localhost

## Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- MongoDB running locally

## Getting Started

### Frontend Setup

```bash
cd octofit-tracker/frontend
npm install
npm run dev
```

The frontend will be available at `http://localhost:5173`

### Backend Setup

```bash
cd octofit-tracker/backend
npm install
npm run dev
```

The backend API will be available at `http://localhost:8000`

## API Endpoints

- `GET /api/health` - Health check endpoint

## Features

- Modern React 19 frontend with Vite
- TypeScript backend with Express
- MongoDB integration with Mongoose
- RESTful API architecture

## Development

### Frontend
- Development: `npm run dev`
- Build: `npm run build`
- Preview: `npm run preview`

### Backend
- Development: `npm run dev`
- Build: `npm run build`
- Start: `npm start`
- Watch: `npm run watch`

---

**OctoFit Tracker** - Your fitness companion powered by modern web technologies.
