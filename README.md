# Video Conferencing App

## Description

A web-based video conferencing application built using React.js. This app allows users to communicate via video calls seamlessly. It leverages WebRTC for real-time video and audioA web-based video conferencing application built using React.js. This app allows users to communicate via video calls seamlessly. It leverages WebRTC for real-time video and audio communication, ensuring a smooth user experience. communication, ensuring a smooth user experience.

## Features

- Peer-to-peer video calling
- Mute/unmute audio
- Enable/disable video
- Room-based conferencing
- Responsive UI

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/SwatiUpadhyay/VConnect.git
   ```
2. Navigate to the project directory:
   ```sh
   cd video-conferencing-app
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Start the development server:
   ```sh
   npm start
   ```

## Deployment

To host your application on GitHub Pages:

1. Install GitHub Pages package:
   ```sh
   npm install gh-pages --save-dev
   ```
2. Add the following scripts to `package.json`:
   ```json
   {
     "scripts": {
       "predeploy": "npm run build",
       "deploy": "gh-pages -d build"
     }
   }
   ```
3. Deploy the app:
   ```sh
   npm run deploy
   ```

## Technologies Used

- React.js
- WebRTC
- Node.js
- Express (if applicable for signaling server)

## Contributing

Contributions are welcome! Feel free to submit a pull request.

## License

This project is licensed under the MIT License.

## Author

Your Name - [GitHub Profile](https://github.com/SwatiUpadhyay)
