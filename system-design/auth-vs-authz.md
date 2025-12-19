# Authentication vs Authorization

## Authentication
Authentication is the process of verifying who a user is.

Example in this app:
- A user logs in with email and password using Firebase Authentication.
- Firebase verifies the credentials and returns an auth token.

Purpose:
- Confirm identity.

## Authorization
Authorization is the process of determining what a user is allowed to do.

Example app:
- Only logged-in users can post content.
- Only tutors can create paid lesson listings.
- Only the owner of a post can delete it.

Purpose:
- Enforce permissions and access control.

## Key Difference
Authentication answers: "Who are you?"
Authorization answers: "What are you allowed to do?"

## Notes
- Authentication happens before authorization.
- A user can be authenticated but not authorized to perform certain actions.
