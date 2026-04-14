# Android Login Application

## 🚀 Author
Bojan Brankovic 

## Project Overview
This project is a simple Android Login Application designed to demonstrate core user authentication functionality, input validation, and session handling in a mobile environment.

The application simulates a real-world login system where users can register, authenticate, and access a protected area of the app.

Authentication in modern Android apps is typically handled via backend services (e.g. Firebase Authentication), where user credentials are validated securely before granting access. :contentReference[oaicite:0]{index=0}

## Features
- User registration (email & password)
- User login
- Input validation (email/password format)
- Error handling for invalid credentials
- Session management (login/logout)
- Navigation to protected screen after login

## Tech Stack
- Java / Kotlin (Android)
- Android SDK
- Firebase Authentication / Backend API (if applicable)
- Android Studio

## Application Flow
1. User opens app  
2. Registers new account or logs in  
3. Credentials are validated  
4. On success → user navigates to home screen  
5. On failure → error message displayed  

## Scope of Testing
- Login functionality (valid/invalid credentials)
- Registration flow
- Input validation
- Error messages
- Session handling (login persistence & logout)
- Navigation flow between screens

## Tools Used
- Manual Testing
- Android Emulator / Real Device
- Logcat (debugging)

## Testing Types
- Functional Testing
- UI/UX Testing
- Negative Testing
- Exploratory Testing
- Regression Testing

## Deliverables
- Test Cases
- Bug Reports
- Test Execution Report

## Key Issues Identified
- Login fails with valid credentials under certain conditions
- Weak password accepted during registration
- Session not cleared after logout
- Error messages not displayed consistently
- App allows empty input submission

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/devbojan/android-login-app.git
