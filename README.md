# API Server for URI Frames


## Step 1: Install dependencies

```bash
yarn install
```

## Step 2: Run the server

```bash
yarn start
```

By default, the server will run on port <http://localhost:3200>. You can modify the port by setting the PORT environment variable.

## Step 3: Deploy on Heroku or Render

```bash
heroku create
heroku buildpacks:set heroku/nodejs
```

And let's push the code to Heroku:

```bash
git push heroku master
```

## Generating JSON data

To generate JSON data, you can use [Mockaroo](https://mockaroo.com/).
