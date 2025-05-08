# Real-Time Chat Application

## Description

This project is a real-time chat application built following a YouTube tutorial by [Surendrakumarpatel](https://www.youtube.com/watch?v=KGH6z0Z0GXA). It features user authentication, profile management, and real-time messaging using Node.js, Express, MongoDB, React, Redux, Socket.io, and Tailwind CSS with Daisy UI. Users can sign up, log in, update profiles, send/receive messages, search for other users, and log out, with a responsive frontend and secure backend.

## Features

- User signup/login with JWT authentication
- Password hashing with Bcryptjs
- Profile photo upload
- Real-time messaging with Socket.io
- Search functionality for users
- Responsive UI with Tailwind CSS and Daisy UI
- State management with Redux
- Persistent store for seamless user experience

## Tech Stack

- **Backend**: Node.js, Express, MongoDB, JWT, Bcryptjs, Socket.io
- **Frontend**: React, Redux, Tailwind CSS, Daisy UI
- **Database**: MongoDB

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Surendrakumarpatel/yt-chat-application.git
   ```

2. Navigate to the project directory:

   ```bash
   cd yt-chat-application
   ```

3. Install backend dependencies:

   ```bash
   npm install
   ```

4. Navigate to the frontend directory and install dependencies:

   ```bash
   cd client
   npm install
   ```

5. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add the following:

     ```env
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```

6. Start the backend server:

   ```bash
   npm run server
   ```

7. Start the frontend development server:

   ```bash
   cd client
   npm start
   ```

## Usage

- Open `http://localhost:3000` in your browser.
- Sign up or log in to start chatting.
- Use the search bar to find other users.
- Send and receive messages in real-time.

## Tutorial Reference

This project was built by following the YouTube tutorial: [Build a Realtime Chat App](https://www.youtube.com/watch?v=KGH6z0Z0GXA).

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License.
