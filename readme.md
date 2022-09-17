# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. [Install Docker](https://docs.docker.com/get-docker/).
2. Verify that Docker has been installed properly by running `docker -v` and `docker-compose -v` in your terminal.
3. Run `docker-compose up` to load Anythink's backend and frontend.
4. Test that the backend is running and connected to your local database by visiting http://localhost:3000/api/ping.
5. Test that the frontend is running and connected to the backend by creating a new user at http://localhost:3001/register.
