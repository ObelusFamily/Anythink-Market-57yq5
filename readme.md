# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Pre-requites

- Docker installed
- docker-compose installed

Steps for setup

1. Clone the repo from Github
2. Navigate to the cloned directory and run `docker-compose up`
3. Check the state by going to `http://localhost:3001/api/ping`
4. Check the front end by going to `http://localhost:3001/register`
5. Register an account
