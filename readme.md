# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
1. Make sure you have [Docker](https://docs.docker.com/get-docker/) installed
2. Clone this repo to your local machine
3. run `docker-compose -v` from the project root directory to start up the development
4. if everything is running correctly, you should be able to access [http://localhost:3000/api/ping](http://localhost:3000/api/ping)
5. try registering an account to make sure everything is is working, through this link [http://localhost:3001/register](http://localhost:3001/register)
