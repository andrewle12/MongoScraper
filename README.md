# The New York Times MongoScraper

## Heroku

https://desolate-tundra-89967.herokuapp.com/

## Requirements to run locally

- Mongoose
- Express
- Express Handlebars
- Axios
- Cheerio

Be sure to run npm install prior to running the app to ensure all the dependencies are installed. The app can be started with node server.js or simply npm start. MongoDB has to also be running locally for database functionality to work.

## Description

The New York Times MongoScraper is an Express node app that scrapes articles from the New York Times' World section. The articles are stored in a Mongo database and users are able to attach a single note to each article. Visiting the /articles route returns a json with all of the articles and attached notes.

![screenshot of app](./public/assets/img/Capture.PNG)

## Author

Andrew Le

## Acknowledgements

UNC Coding Bootcamp at Chapel Hill
