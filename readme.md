# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
1)Clone repo
Clone the repo using either git or a git manadger

2) Install Docker
https://docs.docker.com/get-docker/

3)Load frontend and backend
In powershell navigate to the REPO
Run the command:
    docker-compose up

4)Check backend
go to website http://localhost:3000/api/ping

5)CHeck frontend
go to website http://localhost:3001/register

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
