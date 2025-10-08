Rural Skill Development Platform

Overview
This project aims to build an AI-powered web platform to help rural youth discover, learn, and apply job-relevant skills using free and affordable online resources.

Monorepo Layout
- backend/ — FastAPI service (Python)
- frontend/ — React + Tailwind app
- docs/ — Architecture and product docs

Quick Start
1) Backend
   - Create and activate a virtualenv
   - Install requirements: python -m pip install -r backend/requirements.txt
   - Run dev server: uvicorn backend.app.main:app --reload
2) Frontend
   - cd frontend && npm install && npm run dev

Deployment
Docker (local or server)
- docker compose up --build

Render (cloud)
- Commit repo to GitHub and import in Render
- Render auto-detects services from render.yaml
- Set env vars (YOUTUBE_API_KEY, LINKEDIN_API_KEY) in Render dashboard


Key Components
- Course Aggregation Engine
- Recommendation Engine (AI/ML)
- Adaptive Assessment Engine
- Progress Tracking and Mastery Model
- Job Mapping and Feed Integration
- Admin Console and Analytics Dashboard

License
MIT


