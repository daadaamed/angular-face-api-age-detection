# angular-face-api-age-detection
A simple project that uses Angular for the frontend and FastAPI for the backend to detect age and mood for the person in front of the camera.

## Frontend
The frontend is built using Angular and the face-api.js library. It captures video from the user's webcam and uses face-api.js to detect the age and mood of the person in front of the camera.

## Backend
The backend is built using FastAPI. It provides API endpoints for processing and storing the data received from the frontend.

## How to Run
1. Clone the repository.
2. Install the dependencies for both the frontend and backend.
3. Start the Angular development server.
4. Start the FastAPI server.

## Frontend Setup
```sh
npm install
npm start
```
## API Server Setup
```sh
cd src
uvicorn main:app --reload
```
