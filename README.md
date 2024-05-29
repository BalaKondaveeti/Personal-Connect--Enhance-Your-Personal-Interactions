# Personal Connect

## Description
Personal Connect is a secure React web application designed to help you manage detailed contact information, making your interactions more personal and memorable. This project leverages Firebase for its backend, including Firestore for data storage and Firebase Authentication for secure user access. The goal is to store comprehensive contact details that can be referenced later, impressing your contacts with your attentiveness and memory.

## Features
- Secure storage of contact information including name, phone number, email, date of birth, marital status, sibling information, etc.
- Firebase Authentication with social sign-in options (Google, Facebook, etc.) for secure access.
- Real-time data synchronization using Firestore.
- Responsive and user-friendly interface built with React.
- Open-source and easily extendable.

## Motivation
The main aim of Personal Connect is to help you remember specific details about individuals, such as whether they have siblings or if they are married. This information can be later used to refer to when meeting them, making your interactions more meaningful and leaving a lasting impression.

## Prerequisites
- Node.js and npm installed on your local machine.
- Firebase account.

## Getting Started
### Clone the repository
```sh
git clone https://github.com/yourusername/personal-connect.git
cd personal-connect
```

### Install dependencies
```sh
npm install
```

### Set up Firebase
- Create a new project in the Firebase Console.
- Enable Firestore and Authentication (choose social sign-in methods you prefer).
- Get your Firebase configuration object from the project settings.

### Configure Firebase in your project
- Create a .env file in the root directory and add your Firebase configuration:
```env
REACT_APP_FIREBASE_API_KEY=your-api-key
REACT_APP_FIREBASE_AUTH_DOMAIN=your-auth-domain
REACT_APP_FIREBASE_PROJECT_ID=your-project-id
REACT_APP_FIREBASE_STORAGE_BUCKET=your-storage-bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your-messaging-sender-id
REACT_APP_FIREBASE_APP_ID=your-app-id
```

### Start the development server
```sh
npm start
```

### Deploy to Firebase Hosting
- Install Firebase CLI if you haven't already:
```sh
npm install -g firebase-tools
```
- Initialize Firebase in your project:
```sh
firebase init
```
- Follow the prompts to set up Firebase Hosting.
- Deploy your app:
```sh
npm run build
firebase deploy
```

## Usage
- **Sign In**: Use the social sign-in options to securely access the application.
- **Add Contact**: Use the form to add a new contact with all relevant information.
- **View Contacts**: View all stored contacts in a list with their detailed information.
- **Update/Delete Contact**: Update or delete contact information as needed.
