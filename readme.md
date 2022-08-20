# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Clone repository https://github.com/ObelusFamily/Anythink-Market-det3m
2. Install Docker.
3. Verify docker is ready by running the following commands in your terminal: `docker -v` and `docker-compose -v`.
4. To load Anythink's backend and frontend, run `docker-compose up` from the project root directory
5. Check backend is working by opening your browser to http://localhost:3000/api/ping
6. Check frontend is working by creating a new user on http://localhost:3001/register
