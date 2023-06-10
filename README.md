# Zoom Clone

This project is a clone of the popular video conferencing platform Zoom. It aims to replicate the core functionalities of Zoom, allowing users to host and join video meetings, chat with participants, and share screens.

<!-- ![Zoom Clone Screenshot](screenshot.png) -->

## Features

- **User Authentication:** Users can create an account and log in to access the application. Passwords are securely stored using encryption techniques.

- **Meeting Hosting:** Users can host video meetings by creating a new meeting room. They can invite participants by sharing a unique meeting ID or a meeting link.

- **Meeting Joining:** Participants can join a meeting by entering the meeting ID or clicking on a meeting link provided by the host. Once in the meeting, they can turn on/off their audio and video.

- **Real-time Video Conferencing:** The application provides real-time video streaming capabilities, allowing participants to see and hear each other during the meeting.

- **Chat Functionality:** Participants can send text messages to each other during the meeting using the built-in chat feature.

- **Screen Sharing:** The host can share their screen with the participants, allowing them to present slides, documents, or any other content.

## Technologies Used

- **Front-end:** HTML, CSS, JavaScript, React.js
- **Back-end:** Node.js, Express.js
- **Database:** MongoDB
- **Real-time Communication:** WebRTC, Socket.IO
- **Video Streaming:** WebRTC, WebSockets
- **Authentication:** JSON Web Tokens (JWT)

## Installation

1. Clone the repository: `git clone https://github.com/KGH1113/zoom-clone.git`
2. Navigate to the project directory: `cd zoom-clone`
3. Install the dependencies:
   - For the server, run `npm install`
   - For the client, navigate to the `client` directory: `cd client` and run `npm install`
4. Set up the environment variables:
   - Rename the `.env.example` file to `.env` in the server directory and provide the necessary values.
   - Rename the `.env.example` file to `.env` in the client directory and provide the necessary values.
5. Start the server: In the server directory, run `npm start`
6. Start the client: In the client directory, run `npm start`
7. Open your browser and visit `http://localhost:3000` to access the Zoom Clone application.

## Contributing

Contributions to the Zoom Clone project are welcome! If you want to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature/your-feature-name`
3. Make your changes and commit them: `git commit -m 'Add some feature'`
4. Push the changes to your fork: `git push origin feature/your-feature-name`
5. Submit a pull request to the main repository.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code for personal or commercial purposes.