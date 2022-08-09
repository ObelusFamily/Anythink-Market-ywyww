# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
1) Install Docker from https://docs.docker.com/get-docker/
2) Run docker-compose up from the project root directory to load Anythink's backend and frontend.
3) Once the container is running, navigate to http://localhost:3001/register and create a user
4) Run all the scripts in the container by running the docker exec command.
