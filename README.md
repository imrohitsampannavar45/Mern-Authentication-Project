
```markdown
# MERN Authentication Project

This project is a full-stack authentication system using the MERN stack (MongoDB, Express.js, React, Node.js) with features like email verification, JWT authentication, and more.

## Features

- User Registration
- User Login
- Password Hashing with Bcrypt
- JWT Authentication
- Email Verification with Nodemailer
- Secure Cookie Management
- Frontend in React

## Prerequisites

Make sure you have the following installed:

- Node.js
- MongoDB
- npm or yarn

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/imrohitsampannavar45/Mern-Authentication-Project.git
   cd MERN-Authentication-Project
   ```

2. Install backend dependencies:

   ```bash
   cd backend
   npm install
   ```

3. Install frontend dependencies:

   ```bash
   cd ../frontend
   npm install
   ```

## Environment Variables

Create a `.env` file in the root directory and add the following variables:

```env
# Server Configuration
PORT=4000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret

# Nodemailer Configuration
EMAIL_HOST=smtp.your_email_provider.com
EMAIL_PORT=your_email_port
EMAIL_USER=your_email
EMAIL_PASS=your_email_password

# Frontend Configuration
REACT_APP_API_URL=http://localhost:5000/api
```

## Running the Project

1. Start the backend server:

   ```bash
   cd backend
   npm run server
   ```

2. Start the frontend server:

   ```bash
   cd ../frontend
   npm start
   ```

## Usage

- Open your browser and navigate to `http://localhost:4000`
- Register a new user
- Login with the registered user credentials
- Verify email using the verification link sent to the registered email
- Access protected routes using JWT authentication

## Contributing

Feel free to fork this project and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or suggestions, feel free to reach out to me at imrohitsampannavar@gmail.com
