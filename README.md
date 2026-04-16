# inventory-management-app

A static inventory management UI built with React and Tailwind via CDN, now with user authentication and database storage.

## Features

- User authentication (login/signup)
- Persistent data storage in Firebase Firestore
- Google-style UI design
- Search and sort functionality
- Real-time inventory management

## Setup

1. Create a Firebase project at https://console.firebase.google.com/
2. Enable Authentication (Email/Password)
3. Enable Firestore Database
4. Get your Firebase config from Project Settings
5. Replace the placeholder config in `index.html` with your actual Firebase config

## Usage

1. Open `index.html` in your browser.
2. Sign up or log in with your email and password.
3. Add inventory items.
4. Data is stored in Firebase Firestore and persists across sessions.

## Hosting

This app is configured for GitHub Pages deployment via GitHub Actions.
