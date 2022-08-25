# Note Taker

## Summary
This simple note taking application allows you to save notes with a title and plain text. Powered by ExpressJS, the Note Taker app makes creating, viewing, and deleting notes very simple and keeps them all in one place.

## Prerequisites
* [NodeJS](https://nodejs.org/)

## Installing

Clone the repository to your local development environment.

```
git clone https://github.com/joehenrickson/note-taker
```

Navigate to the developer-profile-generator folder using the command prompt.

Run `npm install` to install all dependencies. To use the application locally, run `node server.js` in your CLI, and then open `http://localhost:3000` in your preferred browswer. The Note Taker app is [live on Heroku](https://radiant-retreat-34618.herokuapp.com/) for you to use as well.

## Preview:
![Application Preview](screencast.webm)

## Deployed Link:
[Note Taker App](https://radiant-retreat-34618.herokuapp.com/)

## Learning Points:
* This app was a practice in writing the backend code only and then integrating it with provided front end code (index.html, notes.html, and custom jQuery)
* Practice setting up an Express server and in particular learning the importance of using the express.static() function to ensure proper delivery of local js/css files used by html files being delivered via .sendFile();

## Built With
* [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
* [NodeJS](https://nodejs.org/)
* Node Packages:
    * [Express](https://www.npmjs.com/package/express)

## Authors
Joe Henrickson
* [GitHub](https://github.com/joehenrickson)
* [LinkedIn](https://www.linkedin.com/in/joseph-henrickson-9a4ba15b/)

## License
This project is licensed under the ISC License.
