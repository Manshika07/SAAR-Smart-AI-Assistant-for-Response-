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



## Assistant Activation
## Assistant Activation & Customization
The virtual assistant only gets activated when you say or type the name of the assistant that you have provided during customization.
For example, if you named your assistant "Shifra", you must include "Shifra" in your command (e.g., "Shifra, what is the weather today?") for the assistant to respond.
This ensures that the assistant listens only for instructions directed to it by name.
You can also customize your assistant's picture during the setup process, choosing from provided images or uploading your own.

## Deployment
You can access the deployed SAAR Virtual Assistant here:
https://saar-smart-ai-assistant-for-response-ukvo.onrender.com
## License
This project is for educational purposes.
