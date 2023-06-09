# No Ads React Weather App

## About

This project is a ReactJS and NodeJS based application that can display weather information.

## Services utilized

The application leverages the [Open-meteo Weather API](https://open-meteo.com/)

## Limitations

The application uses the first result of the place name lookup.
In future versions this will be addressed so the user can select the place name if there are multiple matches.

## Installation

### Requirements

You need to have at least NodeJS 16 installed to run the app locally.

### Running the server

Simply run the following commands inside the server directory

```
    npm install
    npm run build
    npm run start
```

You should see a message "App listening on the port 3000".

### Running the client

Simply run the following commands inside the server directory

```
    export PORT=3001
    npm install
    npm run start
```

Hint: You could also put the PORT into a .env file

##