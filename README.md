

# Basic Login Authentication System using Firebase and Bootstrap : 

This project is a basic authentication system implemented using Firebase Authentication for user authentication and Bootstrap for front-end styling. It allows users to register, login, and sign out.

## Features

### 1. User Registration
   - Users can register by providing their first name, last name, email address, and password.
   - Upon successful registration, user data is stored in Firebase Realtime Database under the "UsersAuthList" node with the user's unique ID as the key.
   
### 2. User Login
   - Registered users can log in using their email address and password.
   - Upon successful login, users are redirected to the home page.
   
### 3. User Authentication
   - Firebase Authentication is utilized for secure user authentication.
   - Passwords are securely hashed and stored in Firebase.
   - Users are authenticated using Firebase's `signInWithEmailAndPassword` method.
   
### 4. Session Management
   - User session data is stored in the browser's sessionStorage.
   - Upon login, user credentials (user ID) and user information (first name, last name) are stored in sessionStorage.
   - Users remain logged in until they manually sign out or clear browser data.
   
### 5. Sign Out
   - Users can sign out by clicking the "Sign Out" button on the home page.
   - Upon signing out, user session data is cleared from sessionStorage and users are redirected to the login page.
   
### 6. Responsive Design
   - Bootstrap is used for front-end styling, ensuring a responsive design that works well on various screen sizes and devices.

## Technologies Used
- Firebase Authentication: Used for user authentication.
- Firebase Realtime Database: Used to store user data.
- Bootstrap 5: Used for front-end styling and layout.
- JavaScript: Used for client-side scripting to interact with Firebase and handle user authentication.

## How to Run
1. Clone the repository to your local machine.
2. Open the project directory in your code editor.
3. Set up Firebase:
   - Create a Firebase project on the Firebase Console.
   - Enable Email/Password authentication in the Firebase project settings.
   - Copy your Firebase project's configuration object (apiKey, authDomain, projectId, etc.) from the Firebase Console.
   - Replace the placeholder Firebase configuration in `login.html` and `register.html` with your Firebase project's configuration.
4. Open the project in a web browser.
5. Register a new user account or log in with existing credentials.
6. Explore the features of the application.

## Contributors
- [Nithin](https://github.com/NithinRoyale/)

