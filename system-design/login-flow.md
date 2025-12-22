# Login Flow

## Overview
This document describes how a user logs into the app using email and password.

## Login basics
- User
- iOS App
- Firebase Authentication
- Firestore Database

## Step-by-Step Flow
1. User enters email and password in the app.
2. App sends credentials to Firebase Authentication.
3. Firebase verifies credentials.
4. If successful:
   - Firebase returns an authentication token.
   - App stores session state.
   - App requests user profile from Firestore.
   - Firestore returns profile data.
   - App navigates user to the main feed.
5. If unsuccessful:
   - Firebase returns an error.
   - App displays an error message to the user.

## Failure Cases
- Incorrect email or password
- Network unavailable
- Firebase service unavailable
- User account does not exist

## Notes
- Passwords are never stored directly in the app.
- Authentication logic is handled by Firebase.
