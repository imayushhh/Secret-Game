This project is a robust authentication system designed to provide secure user management for web applications. It incorporates several advanced security features and follows best practices to ensure data protection and user privacy. The system includes:

User Registration: Users can sign up using their email and password, with data securely stored and managed.
Encryption and Hashing: Passwords are encrypted and hashed using industry-standard algorithms to prevent unauthorized access.
Password Salting: Each password is salted before hashing, enhancing security against rainbow table attacks and brute force methods.
Cookie and Session Management: Handles user sessions and cookies securely to maintain user state and protect against session hijacking.
Environment Variables: Sensitive information such as API keys and configuration settings are stored securely using environment variables to prevent exposure.
OAuth Integration: Implements "Sign In with Google" functionality, allowing users to authenticate using their Google account for a seamless login experience.
Secrets Submission: Enables users to securely submit and manage their secrets within the application.



Technologies Used:

Backend Framework: Express.js
Database: MongoDB with Mongoose
Authentication: Passport.js
Encryption: bcrypt
OAuth: Google
Environment Management: dotenv
