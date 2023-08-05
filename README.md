# Chat-Application
This is a real-time chat application built using React and Firebase, with Google Sign-In authentication. Users can sign in using their Google accounts and participate in chat conversations with other users in real-time.

## Prerequisites
Make sure you have the following software installed on your local machine:

- Node.js (https://nodejs.org/)
- npm (Node Package Manager, comes with Node.js)

## Installation
1. Clone the repository to your local machine.
2. Install the project dependencies.
3. Create a new Firebase project at the Firebase Console. You'll need to sign in with your Google account if you haven't already.
4. Enable Google Sign-In authentication in your Firebase project:
   - Go to the Firebase Console, select your project, and navigate to "Authentication" in the left-hand menu.
   - Choose the "Sign-in method" tab and enable "Google" as a sign-in provider.
5. Create a new web app in the Firebase Console:
   - In the Firebase Console, go to the project overview and click on "Add app" (</>).
   - Select "Web" and follow the setup instructions to register your app.
   - Once completed, you'll receive your Firebase configuration keys (apiKey, authDomain, projectId, etc.).
6. Start the development server

## Features
- Google Sign-In: Users can log in with their Google accounts.
- Real-time Chat: Users can participate in real-time chat conversations.

## Technologies Used
- React: Frontend framework for building user interfaces.
- Firebase: Backend-as-a-Service platform for real-time data synchronization and authentication.
- Google Sign-In: OAuth 2.0 based authentication for user login using Google accounts.

## Firebase Configuration
The application uses Firebase for authentication and real-time data synchronization. Ensure you have set up your Firebase project correctly and replaced the configuration keys.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open a pull request.

## License
This project is licensed under the MIT License.
