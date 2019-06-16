# Twitch-Streaming-React
* Twitch-Streaming-React is a clone of Twitch. Twitch is considered as the world's leading live streaming platform for gamers and the things we love. 
* Integrated with OBS (Open Broadcaster Software), it is a free and open-source cross-platform streaming and recording program built with Qt and maintained by the OBS Project. 
There are versions for Windows, macOS and Linux distributions, such as Ubuntu. 

## Available Scripts
In the project directory, you can run:

## Setup

* Go to the client folder and run `npm i`
* Then go to the api folder and run `npm i`
* Then go to the rmtpServer folder and run `npm i`
* Install OBS in you system and setup basic streaming
* Then to start stream go to OBS settings, then navigate to streams, select custom and paste `rtmp://localhost/live` in server input
* Then get an API key for Google OAuth Login from Google Api
* Then in the client folder make a .env file and paste you api key along with the following variable: `REACT_APP_GOOGLE_CLIENT_ID`. Example: REACT_APP_GOOGLE_CLIENT_ID="XXYYZZ".
* Open three terminal sessions and in one session navigate to the client folder and run npm start, then navigate to rmtpServer folder and run npm start and then navigate to api folder and run npm start.
* The client side will run on Port 3000, RMTP will run on Port 8000 and api side will run on Port 3001

### `npm start`
Runs the app in the development mode.
Open http://localhost:3000 to view it in the browser.

The page will reload if you make edits.
You will also see any lint errors in the console.
