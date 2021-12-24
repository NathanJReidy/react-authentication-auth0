## Get Started

## Frontend

Create `.env` file under the frontend/ directory:

```bash
cd frontend/
touch .env
```

Update the frontend .env file with the required environment variables:

```bash
REACT_APP_AUTH0_DOMAIN=<your auth0 domain>
REACT_APP_AUTH0_CLIENT_ID=
REACT_APP_AUTH0_AUDIENCE=
REACT_APP_SERVER_URL=http://localhost:6060
```

Install the frontend project dependencies in the frontend/ directory:

```bash
npm install
```

Run the frontend, from the frontend/ directory:

```bash
npm start
```

The application runs on port 4040.

Visit http://localhost:4040/ to access the starter application.

## Backend

Create `.env` file under the backend/ directory:

```bash
cd backend/
touch .env
```

Update the backend .env file with the required environment variables:

```bash
SERVER_PORT=6060
CLIENT_ORIGIN_URL=http://localhost:4040
AUTH0_AUDIENCE=
AUTH0_DOMAIN=
```

Install the backend project dependencies in the backend/ directory:

```bash
npm install
```

Run the backend, from the backend/ directory:

```bash
npm start
```

## Other

This starter template was configured by following the auth0 react guide:
https://auth0.com/blog/complete-guide-to-react-user-authentication/
