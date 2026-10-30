# Smart Student Task Management System

A web app for students to manage tasks, deadlines, study plans and study materials.

**Current status: Phase 1 (frontend with sample local data).** No AWS services are connected yet.

## Planned architecture

React (Vite) -> API Gateway -> Lambda (Python) -> DynamoDB
File upload/download: React -> Lambda creates S3 presigned URL -> React talks to S3 directly.

## Features (Phase 1)

- Dashboard with task statistics, completion ring and upcoming deadlines
- Task create / edit / delete / mark complete, with search and filters
- Rule-based study planner with deadline highlighting
- Study materials page with file type and size validation (local demo only)
- Responsive layout (sidebar on desktop, bottom bar on mobile)

## Run locally

Requires Node.js 18 or newer.

```powershell
cd frontend
npm install
npm run dev
```

Open http://localhost:5173

## Roadmap

1. Phase 1: React frontend with sample data (this version)
2. Phase 2: Task CRUD with Python Lambda + DynamoDB
3. Phase 3: S3 upload/download with presigned URLs
4. Phase 4: Planner, filters and dashboard stats from the API
5. Phase 5: Cognito authentication
6. Phase 6: Deployment, CORS and testing

## Screenshots

(Add screenshots here later)
