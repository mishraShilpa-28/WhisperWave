# Real-Time Chat Application

## Description

This project is a real-time chat application. It features user authentication, profile management, and real-time messaging using Node.js, Express, MongoDB, React, Redux, Socket.io, and Tailwind CSS with Daisy UI. Users can sign up, log in, update profiles, send/receive messages, search for other users, and log out, with a responsive frontend and secure backend.

### Live Demo

- [Live demo link](https://whisperwave-g6y1.onrender.com)

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
   git clone https://github.com/mishraShilpa-28/WhisperWave.git
   ```

2. Navigate to the `root` project directory:

   ```bash
   cd WhisperWave
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add the following:

     ```bash
      PORT = 8080
      MONGO_URI=
      JWT_SECRET_KEY=
     ```

5. Build the app:

   ```bash
   npm run build
   ```

6. Start the backend server with frontend:

   ```bash
   npm run server
   ```

## Usage

- Open `http://localhost:3000` in your browser.
- Sign up or log in to start chatting.
- Use the search bar to find other users.
- Send and receive messages in real-time.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License.