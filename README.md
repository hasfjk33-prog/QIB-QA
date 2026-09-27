# QIC Car Insurance Flow

A static HTML car insurance flow served by an Express application, with an admin dashboard and visitor tracking API.

## Run locally

```sh
npm install
npm start
```

Open `http://localhost:3000`. Set `PORT` to use a different port and set `ADMIN_PASSWORD` to configure the admin password.

## Project layout

- `public/`: customer flow pages and admin dashboard
- `server.js`: Express server and API routes
- `package.json`: scripts and dependencies