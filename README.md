# azure-ad-login
This is the repository containing the azure ad login.

## Folder Structure

The repository consists mainly of two essential folders i.e. frontend and backend. The respective readme files with their folder structure are mentioned below:

[Frontend README](frontend/README.md)

[Backend README](backend/README.md)


## Installation Prequisites

To ensure the project runs smoothly, please make sure your application meets the following requirements in development/production:

* Node.js >= `18`

## Quick Start

To run the sofy docs project locally in Visual Studio Code perform the following steps:

1. Clone the repository to your local machine:
```sh
$ git clone https://github.com/patraAmarendra/azure-id-login.git
```

2. Install frontend/backend dependencies with npm:

```sh
$ npm run install:all
```

3. Setup the configuration for both frontend and backend by:
* Adding the `.env` files or renaming the `sample.env` files present in frontend/backend respectively  to `.env` and updating the environment variables.

* These keys need to be configured as environment variables in the web app.


frontend/.env
```
VUE_APP_PLATFORM_DOCS_TARGET_URL=
```

backend/.env
```
JWT_ENCRYPTION_KEY=
ENV_CONTEXT=
SESSION_SECRET=
REDIS_SERVER_URL=
REDIS_SERVER_PORT=
REDIS_SERVER_PASSWORD=
CLIENT_ID=
IDENTITY_METADATA=
REDIRECT_URL=
```

4. Start the backend by running the below command in a separate window

```sh
$ npm run backend
``` 
