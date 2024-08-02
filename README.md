# Real-Time Chat Application with MERN Stack, Socket.io, Redux Toolkit, and Tailwind CSS

This project is a dynamic real-time chat application enabling users to connect and communicate instantly. Built with the MERN stack (MongoDB, Express.js, React.js, and Node.js), along with Socket.io for real-time functionality, Redux Toolkit for state management, and Tailwind CSS for styling.

- If you enjoyed this project, please star the repository! ⭐
- Watch a demo on YouTube: [Click Here](https://youtu.be/11oZj2jBhOE)

## Tech Stack

- **MERN stack**: MongoDB, Express.js, React.js, Node.js
- **Real-time communication**: Socket.io
- **State management**: Redux Toolkit
- **Styling**: Tailwind CSS

## Key Features

- **Real-time Messaging**: Instant message exchange between users.
- **User Authentication**: Sign up, log in, and log out with JWT and Google Auth.
- **Group Chats**: Create and join chat rooms.
- **Notifications**: Get notified on new messages.
- **Emojis**: Send and receive emojis.
- **Profile Management**: Update avatar and display name.
- **Room Creation**: Create private chat rooms.
- **Search Functionality**: Easily find users or messages.
- **Responsive Design**: Optimized for various devices and screen sizes.

## Getting Started

To run this project locally, follow these steps:

1. **Clone the Repository**:
    - Fork and clone the repository, or download the ZIP file and unzip it.

2. **Open in Code Editor**:
    - Use your preferred code editor to open the project.

3. **Set Up Environment Variables**:
    - Split the terminal into two (one for the client and one for the server).

### Client Setup

1. Navigate to the client directory:
    ```bash
    cd client
    ```

2. Create a `.env` file in the root of the client directory with the following content:
    ```env
    REACT_APP_GOOGLE_CLIENT_ID=
    REACT_APP_SERVER_URL='http://localhost:8000'
    ```

3. Get your Google Client ID:
    - Visit the [Google Cloud Credentials Page](https://console.cloud.google.com/apis/credentials).
    - Create a new project if necessary, then follow these steps:
        - Click **Create credentials** > **OAuth client ID**.
        - Select **Web application**.
        - Name your OAuth client and click **Create**.
        - Provide the domain and redirect URL (http://localhost:3000 and http://localhost:3000/login for development).
        - Copy the Client ID and paste it into `REACT_APP_GOOGLE_CLIENT_ID`.

4. Install dependencies and start the client:
    ```bash
    npm install
    npm start
    ```

### Server Setup

1. Navigate to the server directory:
    ```bash
    cd server
    ```

2. Create a `.env` file in the root of the server directory with the following content:
    ```env
    PORT=8000
    URL=
    SECRET=
    CLIENT_ID=
    BASE_URL="http://localhost:3000"
    ```

3. Install dependencies and start the server:
    ```bash
    npm install
    npm start
    ```

## Contributing

Contributions are highly encouraged! If you discover a bug or have an idea for a new feature, please submit an issue or a pull request. Here's how to contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b my-new-feature`.
3. Commit your changes: `git commit -m 'Add new feature'`.
4. Push to your branch: `git push origin my-new-feature`.
5. Open a Pull Request.

---
