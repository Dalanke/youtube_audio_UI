# Teatime_Music_UI
This is the UI code for the website **Teatime music** that streaming audio from youtube videos.

The back-end code and project **README** can be found there:<br>
https://github.com/Dalanke/youtube_audio_API

Visit the live demo at:<br>
https://stayhome-ui.herokuapp.com/

Interested in audio player component? Check the code of React audio player at:<br>
https://github.com/Dalanke/react_audio_player

## Environment variable setting

Creat `.env` file and sets a variable per line for local testing and depolyment:
```bash
# GraphQL API end point, Uncomment this line for deployment/comment out for local usage
REACT_APP_API_ENDPOINT=https://<your api host>/graphql
# Currently use ReCAPTCHAv2
REACT_APP_RECAPTCHA_KEY=<your recaptcha site key> 
```

## Notes:
* This App is created by [create-reat-app](https://create-react-app.dev/)

* If `npm start` failed with below error:
  ```
  Attempting to bind to HOST environment variable: x86_64-apple-darwin13.4.0
  If this was unintentional, check that you haven't mistakenly set it in your shell.
  Learn more here: https://bit.ly/CRA-advanced-config

  events.js:292
      throw er; // Unhandled 'error' event
      ^

  Error: getaddrinfo ENOTFOUND x86_64-apple-darwin13.4.0
  ```
  Run `unset HOST` in terminal and try again

