# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install Docker: https://docs.docker.com/get-docker/
2. **Clone** this repository (do not create Fork)
3. From the project root directory run ```docker-compose up```
4. To test if everything is working visit in your browser: http://localhost:3000/api/ping
