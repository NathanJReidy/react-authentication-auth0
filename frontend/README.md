# Easy User Authentication for React Apps

This repository hosts a React project that defines a Single-Page Application (SPA). You'll secure access to some of its routes using Auth0 User Authentication.

## Get Started

Create `.env` file under the frontend/ directory:

```bash
touch .env
```

Update the frontend .env file with the required environment variables:

```bash
REACT_APP_AUTH0_DOMAIN=
REACT_APP_AUTH0_CLIENT_ID=
REACT_APP_AUTH0_AUDIENCE=
REACT_APP_SERVER_URL=http://localhost:6060
```

Install the client project dependencies:

```bash
npm install
```

Run the client project:

```bash
npm start
```

The application runs by on port 4040 to mitigate conflicting with other client applications you may be running.

Visit http://localhost:4040/ to access the starter application.
