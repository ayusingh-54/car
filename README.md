# Car Project

## Description
A web application built with React and Vite, featuring authentication with Clerk.

## Technologies
- React
- Vite
- React Router
- Clerk Authentication

## Prerequisites
- Node.js and npm installed
- Clerk account and API keys

## Setup
1. Clone the repository
2. Install dependencies:
```bash
cd vite-project
npm install
```

3. Create a `.env` file in the root directory and add your Clerk publishable key:
```
VITE_CLERK_PUBLISHABLE_KEY=your_publishable_key_here
```

4. Start the development server:
```bash
npm run dev
```

## Project Structure
- `/src`: Source files
  - `main.jsx`: Entry point with routing and Clerk configuration
  - `home.jsx`: Home page component
  - `App.jsx`: Main application component

## Authentication
This project uses Clerk for authentication. Users can sign in through the interface provided by Clerk.

## License
[Your chosen license]
