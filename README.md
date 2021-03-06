## Search for attractions by location using the Yelp API

Web app I created over a couple of days in Aug. 2017 using `React` and `Express`.

## Built with `create-react-app`

Connected to a [Node Express API server](https://www.fullstackreact.com/articles/using-create-react-app-with-a-server/).

## To run

Obtain a client id and secret for the [Yelp Fusion API](https://www.yelp.com/developers/documentation/v3/authentication).

Create an `app-env` file in the main directory and save the id and secret.

```
// Inside app-env
export CLIENT_ID='CLIENT_ID'
export CLIENT_SECRET='CLIENT_SECRET'
```
Source the file into the local environment.

```
source app-env
```

Install and start. App will automatically open at [localhost:3000](http://localhost:3000/).

```
npm i

cd client
npm i

cd ..
npm start
```

## Deployed version

Available on [Heroku](https://rowan-test.herokuapp.com/).
