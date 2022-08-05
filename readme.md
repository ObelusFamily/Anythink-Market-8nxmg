# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

* [Download](https://docs.docker.com/get-docker/) docker for your local machine.  
* Once installed, verify that docker is running with `docker -v` and `docker-compose -v`.
* Once that is confirmed, run `docker-compose up` from project root directory to start the backend and frontend.
