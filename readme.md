# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

Go ahead and create your own codespace , I'll wait.
3:05
(No need to change anything in the default options, just click on the Create codespace button and wait for it to boot)
3:09
Great! Looks like your codespace is up and running. You can now run docker-compose up in your codespace's terminal to load Anythink's backend and frontend.
3:09
Once docker-compose finishes loading up, the backend should be running and able to connect to the database.
3:09
Let's test this by pointing your browser to https://obelusfamily-anythink-market-d9nr4-5jvv664wxxp24xxg-3000.githubpreview.dev/api/ping

Ness
3:16 PM
Easy Peasy! The backend is up and running.
3:16
Now, it’s time to check the frontend and make sure it’s connected to the backend.
3:17
If everything is working properly, you’ll be able to create a new user on https://obelusfamily-anythink-market-d9nr4-5jvv664wxxp24xxg-3001.githubpreview.dev/register
3:17
Create one (choose a cool nickname and everything) and you’ll be able to move to the next task.
3:17
Ooohh, I didn’t expect you to do this so quickly! Even your username, wrpspdchc, brings back memories. Strangely enough, they’re your memories, which I don’t know why I have.
3:17
Never mind that, though—you’re done with this dib.
3:17
Just make sure that you run all scripts in the next quests on one of the containers created by docker-compose up.  Also, you can use docker exec to run commands on a running container.
3:17
It looks like your environment is ready! 😀