# React Chat Bot

A React-based chat bot application with Firebase integration for authentication and real-time chat functionality.

## Features

- User Authentication (Email/Password and Google Sign-in)
- Real-time chat functionality
- Firebase Firestore integration
- Material-UI components
- TypeScript support

## Setup

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file in the root directory with your Firebase configuration:
   ```
   REACT_APP_FIREBASE_API_KEY=your-api-key
   REACT_APP_FIREBASE_AUTH_DOMAIN=your-auth-domain
   REACT_APP_FIREBASE_PROJECT_ID=your-project-id
   REACT_APP_FIREBASE_STORAGE_BUCKET=your-storage-bucket
   REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your-messaging-sender-id
   REACT_APP_FIREBASE_APP_ID=your-app-id
   REACT_APP_FIREBASE_MEASUREMENT_ID=your-measurement-id
   ```
4. Start the development server:
   ```bash
   npm start
   ```

## Available Scripts

- `npm start`: Runs the app in development mode
- `npm test`: Launches the test runner
- `npm run build`: Builds the app for production
- `npm run eject`: Ejects from Create React App

## Technologies Used

- React
- TypeScript
- Firebase (Authentication & Firestore)
- Material-UI
- React Router

## License

MIT
