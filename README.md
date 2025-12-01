# Secret – Personal Secret Storage Website

A secure web application for storing personal secrets, built using **Node.js**, **Express.js**, **PostgreSQL**, and **EJS**, following **RESTful design principles**.

The app allows users to register and log in securely, store confidential notes, and optionally authenticate via **Google OAuth**.

---

## Features

### User Authentication
- Secure login and registration using username/password  
- Session-based authentication to keep users logged in  
- Google OAuth login for faster and secure access  

### Data Security
- Passwords hashed with **bcrypt**  
- Input validation to prevent malicious data  
- Structured error handling for reliability  

### Secret Management
- Store personal secrets securely  
- Retrieve secrets after authentication  
- Submit and update secrets  

### RESTful Architecture
- Clear and organized routing for resources  
- Easy to extend and maintain  

---

## Tech Stack
- **Backend:** Node.js, Express.js  
- **Database:** PostgreSQL  
- **Authentication:** Passport.js (Local & Google OAuth2)  
- **Frontend:** EJS templates  
- **Security:** bcrypt, express-session, input validation
