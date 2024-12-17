# Project Workflow

## Frontend

1. User accesses the camera via `CameraModule.js`.
2. Sends video frames (or snapshots) to the AI Flask API.
3. Displays posture feedback and exercise suggestions on the dashboard.

## Backend

1. Authenticates users (login/signup).
2. Stores workout logs, user progress, and personalized plans.
3. Acts as a proxy to communicate securely with the AI service.

## AI Service

1. Receives video frames.
2. Runs pose detection and equipment recognition.
3. Sends feedback (posture corrections, equipment suggestions).