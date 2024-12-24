# Login and Authentication Project with MongoDB

This project implements a simple login and logout authentication system with the following features:
- **Login page** for users to log in.
- **Logout functionality** to securely end user sessions.
- **Home page** that is accessible only to authenticated users.
- **Secret page** that is protected and can only be accessed by logged-in users.
- **Password hashing** for secure password storage.
- **MongoDB** for storing user data.

### Technologies Used:
- **JavaScript (Node.js)**
- **Express**: Web framework to handle routes and middleware.
- **MongoDB**: NoSQL database to store user data.
- **Mongoose**: MongoDB object modeling for Node.js.
- **Bcrypt**: Password hashing library.
- **Express-session**: Middleware to manage sessions.

### Features:
1. **Login & Logout**:
    - Users can log in with a username and password.
    - Passwords are securely hashed using `bcrypt` before being stored in MongoDB.
    - Sessions are managed using `express-session`, ensuring secure and persistent logins.
    - Logged-in users can access the protected **Home** and **Secret** pages.
  
2. **Home Page**:
    - A page accessible to logged-in users only.

3. **Secret Page**:
    - A page that is protected and only accessible by authenticated users.

4. **Password Hashing**:
    - The user's password is hashed before being saved into the database using `bcrypt` to ensure security.

