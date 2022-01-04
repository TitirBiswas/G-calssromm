# G-Classromm

## Installing dependencies

> git clone https://github.com/TitirBiswas/Smart-Classroom G-Class

- Inside `server` folder, create a new file called `.env` which stores your `ATLAS_URI`, `SECURITY_KEY` and `CLIENT_URL` information
  - store your database URI inside `ATLAS_URI` variable
  - store your security key inside `SECURITY_KEY` variable
  - store your client url inside `CLIENT_URL` variable
  - example:
  ```
  ATLAS_URI =mongodb+srv://admin:<password>@cluster0.8aezk.gcp.mongodb.net/classroom?retryWrites=true&w=majority
  SECURITY_KEY = A73373D9B4ED6FEC5B8B2DAF6WA9XMCU3487C88B196EBDCCEA77AFF7C2
  CLIENT_URL = http://localhost:3000/
  ```
- Inside `client` folder, create a new file called `.env` which stores your `REACT_APP_SECURITY_KEY` and `REACT_APP_BACKEND_URL` informations

  - store your security key inside `REACT_APP_SECURITY_KEY` variable, note that this value must same as `SECURITY_KEY` in `server/.env` file
  - store your server url inside `REACT_APP_BACKEND_URL` variable
  - example:

  ```
  REACT_APP_SECURITY_KEY = A73373D9B4ED6FEC5B8B2DAF6WA9XMCU3487C88B196EBDCCEA77AFF7C2
  REACT_APP_BACKEND_URL = http://localhost:5000
  ```

> cd G-Class

## Installing dependencies for frontend

> cd client

> npm install

## Installing dependencies for backend

> cd server

> npm install

## Run backend

> cd server

> node index.js

## Serve frontend

> cd client

> npm start

