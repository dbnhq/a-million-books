# Book Search Engine

## Description

A MERN stack application using the Google Books API for dynamically rendered search results that can be stored or deleted.

# Install

Run `npm run install:all` to install dependencies for the root, client, and server.

You need a local MongoDB instance running (the server connects via `server/config/connection.js`).

# Run

- `npm run dev` — starts the React client (port 3000) and the Express/GraphQL server (port 3001) together.
- `npm run build && npm start` — builds the client and serves it from the Express server in production mode.

