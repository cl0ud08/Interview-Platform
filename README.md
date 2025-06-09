# Interview Platform

A modern web-based interview platform designed to facilitate seamless candidate assessments through video calls, quizzes, and authentication.

---

## &#9881; Technology Stack

- **React & Redux**: For building a responsive and scalable frontend with state management.
- **Material UI & SASS**: For sleek UI components and modular styling.
- **Firebase Authentication**: 
  - Sign-in workflow supporting multiple providers:
    - Google Sign-In
    - GitHub Sign-In
    - Facebook Login
  - Handles account-exists errors gracefully when signing in with different credentials.
- **Redux-Redirect**: Automatically redirects users to the Quiz page upon successful login.
- **Firestore Database**: Stores quiz data and user progress securely in the cloud.
- **Redux-thunk**: Manages asynchronous calls and side effects for fetching and storing data.

---

## Features

- Multiple social sign-in options for easy and secure authentication.
- Robust error handling for credential conflicts.
- Seamless redirect to quizzes post-login.
- Real-time storage and retrieval of quiz data with Firestore.
- Clean, modern UI with Material UI components and custom SASS styling.

---

## Getting Started

### Prerequisites

- Node.js (v14 or higher recommended)
- npm or yarn package manager
- Firebase account and project setup

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/cl0ud08/Interview-Platform
   cd interview-platform
