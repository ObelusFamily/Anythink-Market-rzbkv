# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

1. download docker from browser and open it up 
2. have the repo already cloned to your machine
3. run "docker -v" and "docker-compose -v" in the terminal to ensure docker works properly
4. run "docker-compose up" to run docker on the whole folder
5. make sure everything works by going to localhost: 3000 and localhost:3001
