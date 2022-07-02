# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Use  __docker-compose up__  from the root directory to start both frontend and backend. 

To check that the backend is up and running, open [http://localhost:3000/api/ping](http://localhost:3000/api/ping).

To check that the frontend is connected to the backend, open [http://localhost:3001/register](http://localhost:3001/register). You should be able to create a new user from there.