# SAAR Virtual Assistant

This project is a full-stack virtual assistant application with a Node.js/Express backend and a React frontend.

## Project Structure

- **backend/**: Node.js/Express server, API routes, controllers, models, and configuration files.
- **frontend/**: React application (Vite), components, pages, and assets.

## Backend
- Express server with authentication and user management
- MongoDB database connection
- API endpoints for authentication and user operations
- Middleware for authentication and file uploads

## Frontend
- React (Vite) SPA
- User authentication (Sign In/Sign Up)
- Home and customization pages
- Context for user state management

## Getting Started

### Prerequisites
- Node.js (v16+ recommended)
- npm or yarn
- MongoDB instance (local or cloud)

### Backend Setup
1. Navigate to the `backend` folder:
   ```sh
   cd backend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Create a `.env` file with your environment variables (see `.env.example` if available).
4. Start the backend server:
   ```sh
   npm start
   ```

### Frontend Setup
1. Navigate to the `frontend` folder:
   ```sh
   cd frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the frontend development server:
   ```sh
   npm run dev
   ```

The frontend will be available at `http://localhost:5173` and the backend at `http://localhost:5000` (or the port specified in your `.env`).

## License
This project is for educational purposes.
