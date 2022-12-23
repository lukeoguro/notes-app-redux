# Notes App using Redux

This is a bare-bone, experimental notes app for practicing Redux with React. It follows University of Helsinki's Full Stack Open.

The app is written using the React-Redux hooks API.
It's only in [`843b218`](/../../commit/843b21889c70b67f6a45e0a2d8930fa62de48c38) where the code is reverted to use the `connects` API for practice purposes.

## Setup

First, run `npm install` and `npm run server` to start the `json-server` backend. Then, run `npm start` to start the React frontend.

## Additional notes

New notes are "not important" by default.
There's no way to configure this from the frontend at the moment, as this is just a practice app.
You can create "important" notes directly in the `db.json` file.

