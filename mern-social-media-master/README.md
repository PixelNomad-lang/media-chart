# MERN Social Media Project

## Overview
The MERN Social Media project is a fully functional social media platform built using the MERN stack (MongoDB, Express.js, React, Node.js). This platform allows users to create accounts, share posts, interact with others, and manage their profiles.

## Features
- **User Authentication:** Secure signup, login, and logout functionality.
- **Profile Management:** Users can create, edit, and update their profiles.
- **Post Creation:** Users can create, edit, and delete posts.
- **Like and Comment:** Engage with posts by liking and commenting.
- **Friend Requests:** Send, accept, or reject friend requests.
- **Real-time Updates:** Updates across the platform using WebSockets.
- **Responsive Design:** Seamless user experience on all devices.

## Tech Stack
- **Frontend:** React, TailwindCSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JSON Web Tokens (JWT), bcrypt
- **Hosting:** Frontend hosted on Vercel, backend hosted on Render

## Installation and Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/PixelNomad-lang/mern-social-media.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd mern-social-media
   ```

### Backend Setup
1. Navigate to the `server` directory:
   ```bash
   cd server
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up your environment variables in a `.env` file:
   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   PORT=5000
   ```
4. Start the backend server:
   ```bash
   npm start
   ```

### Frontend Setup
1. Navigate to the `client` directory:
   ```bash
   cd client
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the frontend development server:
   ```bash
   npm run dev
   ```

## Usage
1. Access the application by navigating to the frontend development server URL (e.g., `http://localhost:5173`).
2. Create a new account or log in with an existing account.
3. Start interacting with the platform by creating posts, liking, commenting, and connecting with other users.

## Folder Structure
```
mern-social-media
├── client
│   ├── src
│   │   ├── components
│   │   ├── pages
│   │   ├── utils
│   └── ...
├── server
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── middleware
│   └── ...
└── README.md
```

## Contributing
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Added new feature"
   ```
4. Push to your fork:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact
For any questions or suggestions, feel free to reach out:
- **Email:** adarshbalmukundshukla@gmail.com
- **GitHub:** [PixelNomad-lang](https://github.com/PixelNomad-lang)
- **LinkedIn:** [Adarsh Shukla](https://www.linkedin.com/in/adarsh-shukla-55825b256/)

