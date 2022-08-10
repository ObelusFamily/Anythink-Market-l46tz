# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install docker on your machine from [here](https://docs.docker.com/get-docker/).
2. Verify that docker has been successfully installed on your machine by running the following commands in your terminal:

   `$ docker -v`

   `$ docker-compose -v`

3. Once you've verified that Docker has been installed successfully, navigate to the root project of the folder and run the following command:

   `$ docker-compose up`

4. If everything worked fine, then you should be get a test response at `http://localhost:3000/api`.

5. And that's it! Your environment is now ready!
