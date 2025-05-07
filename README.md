# copilot-training

## Description

This mono repository resembles a simple full stack application to demonstrate the use of GitHub Copilot while developing.

The Application stores and displays profiles of cats.

## Tech Stack

- Frontend - Angular
- Persistence - Postgre SQL
- Backend - JAVA (Spring)

## Project Setup and Startup

### Backend Setup
1. Navigate to the `backend` directory:
   ```bash
   cd backend
   ```
2. Build the project using Maven:
   ```bash
   ./mvnw clean install
   ```
3. Start the backend server:
   ```bash
   ./mvnw spring-boot:run
   ```

### Frontend Setup
1. Navigate to the `frontend` directory:
   ```bash
   cd frontend
   ```
2. Install the dependencies:
   ```bash
   npm install
   ```
3. Start the frontend development server:
   ```bash
   npm start
   ```

### Accessing the Application
- The backend server will run on `http://localhost:8080`.
- The frontend application will run on `http://localhost:4200`.