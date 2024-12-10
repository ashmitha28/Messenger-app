# Firebase Chat Application

## Description
This is a Messenger app made for Ios devices using Swift UIKit. The app utilizes **Firebase Authentication** and **Firestore Database** to implement a chat application that supports user registration, login/logout functionality, and one-on-one messaging. The main goal is to create a usable design and implement the required features.

## Features
### Authentication
- **Register**: Users can register with their name, email, and password, including a repeat password field for validation.
- **Login**: Users can log in using their registered email and password.
- **Logout**: Users can log out of the application.

### Chat Functionality
- **Chat List Screen**: Displays a list of all authenticated users who are considered "friends."
- **One-on-One Chat**: 
  - Users can send text messages to their friends.
  - Messages display:
    - Sender's name.
    - Text content.
    - Date and time of the message.
  - Messages are styled distinctly for the sender and the receiver (e.g., different alignments or background colors).
  - The chat screen scrolls automatically to the latest message.

### Additional Requirements
- Handles invalid input gracefully with user-friendly error alerts.
- Fully usable design with no specific design provided by the instructor.

## Technology Stack
- **Programming Language**: Swift
- **UI Framework**: UIKit
- **Backend**: Firebase Authentication, Firestore Database
- **Other Tools**: Xcode


