# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install [install Docker](https://docs.docker.com/get-docker/).
2. Clone frontend and backend repositories ([frontend](frontend/readme.md) and [backend](backend/README.md)).
3. Verify docker is ready by running the following commands in your terminal: `docker -v` and `docker-compose -v`.
4. Run docker-compose up from the project root directory to load backend and frontend.
5. If docker is working correctly, the backend should be running and able to connect to your local database. Test this by pointing your browser to `http://localhost:3000/api/ping`
6. Frontend should load automatically with the address of `http://localhost:3001/`
7. Good luck!