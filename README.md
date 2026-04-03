# Todo List

[![React](https://img.shields.io/badge/React-16.13-61DAFB?logo=react&logoColor=white)](https://reactjs.org/)
[![Firebase](https://img.shields.io/badge/Firebase-7-FFCA28?logo=firebase&logoColor=black)](https://firebase.google.com/)
[![Material UI](https://img.shields.io/badge/Material_UI-4-007FFF?logo=mui&logoColor=white)](https://mui.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3.8-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)

A task management web application built with React and Firebase, featuring user authentication, multiple task lists, and real-time cloud sync. Create, organize, and track your daily tasks with a clean Material UI interface.

## Features

- **User Authentication** — Secure login and registration with Firebase Auth
- **Multiple Task Lists** — Create and manage separate lists for different categories
- **Task Management** — Add, edit, delete, and mark tasks as complete/incomplete
- **Search** — Filter through tasks quickly with built-in search functionality
- **Real-Time Sync** — All data stored in Firebase Firestore with instant updates
- **Responsive Design** — Material UI components that adapt to any screen size
- **Protected Routes** — Only authenticated users can access their task lists

## Tech Stack

| Technology | Purpose |
|-----------|---------|
| **React 16** | Component-based UI with Hooks |
| **Firebase Auth** | User authentication (email/password) |
| **Firebase Firestore** | Real-time NoSQL database |
| **Material UI 4** | Pre-built React components and icons |
| **React Router v5** | Client-side routing |
| **Bootstrap 4** | Additional layout utilities |

## Project Structure

```
Todo-List/
├── public/
├── src/
│   ├── app/
│   │   ├── assets/              # Icons and images
│   │   ├── components/
│   │   │   └── todoItemList.jsx  # Task item component
│   │   ├── screens/
│   │   │   ├── Home/            # Main todo list view
│   │   │   ├── Login/           # Login page
│   │   │   └── Register/       # Registration page
│   │   └── services/
│   │       └── firebase.js      # Firebase configuration
│   ├── App.js                   # Root component with routing
│   └── index.js                 # Entry point
├── tsconfig.json
├── package.json
└── README.md
```

## Getting Started

### Prerequisites

- Node.js 14+
- A Firebase project with Firestore and Authentication enabled

### Installation

```bash
git clone https://github.com/gautammanak1/Todo-List.git
cd Todo-List
npm install
```

### Firebase Setup

1. Create a project at [Firebase Console](https://console.firebase.google.com/)
2. Enable **Email/Password** authentication
3. Create a **Firestore** database
4. Update `src/app/services/firebase.js` with your Firebase config

### Run

```bash
npm start
```

The app will open at [http://localhost:3000](http://localhost:3000).

## License

This project is open source and available under the [MIT License](LICENSE).
