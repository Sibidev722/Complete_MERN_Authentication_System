Complete MERN Authentication System
A full-stack MERN authentication system that provides a modern, secure, user-friendly login and sign-up experience. The system includes email OTP verification, login confirmation emails, password hashing, and secure JWT-based authentication, with a clean React frontend that automatically generates a profile icon for each user.

✨ Features
✅ User Registration:

New users can sign up through a registration form.

After signing up, an OTP verification email is sent to the registered address.

The user must verify their email via OTP before logging in.

✅ User Login:

Existing users can securely log in using email and password.

On successful login, a confirmation email is sent to the user’s email address.

Passwords are hashed using bcrypt for secure storage.

✅ Profile Icon:

After login, the system automatically generates a profile icon displaying the first letter of the user’s name.

The profile icon includes options to log out and verify email if not verified yet.

✅ Email Verification:

Email verification is handled using OTP codes sent to the user’s registered email.

Users can re-trigger verification from their profile if needed.

✅ Reset Password:

Users can reset forgotten passwords.

A secure OTP is sent to the email, which must be entered to reset the password.

✅ Protected Routes:

JWT-based authentication protects backend API routes.

The React frontend uses route guards to restrict access to authenticated users only.

✅ Secure Communication:

Axios handles HTTP requests between frontend and backend.

CORS is configured for secure cross-origin requests.

## 🛠️ Tech Stack
- Frontend: React, React Router, Axios
- Backend: Node.js, Express.js
- Database: MongoDB with Mongoose
- Auth: JWT, bcrypt, nodemailer for OTP emails
- Security: CORS
