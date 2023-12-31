# Your Spotify playback ranking
Inspired by a [Spotify Authorization Code example](https://github.com/spotify/web-api-examples/tree/master/authorization/authorization_code).

## Installation
```
npm install
```

## Using your own credentials
You will need to register your app and get your own credentials from the [Spotify for Developers Dashboard](https://developer.spotify.com/dashboard).

- Create a new app in the dashboard and add `http://localhost:8888/callback` to the app's redirect URL list.
- Once you have created your app, update the `client_id` and `client_secret` in the `.env` file with the credentials obtained from the app settings in the dashboard.

## Running the example
```
npm start
```

Then, open `http://localhost:8888` in a browser.
