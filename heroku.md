# Heroku

```
heroku login
```

-- Used to login into heroku CLI

go into github repo folder

```
$ heroku create
```

This will create your app on Heroku (which prepares Heroku to receive your source code) and generates two links:

- Fhe first URL will be the live page
- The second link is the GitHub repo provided by Heroku you’ll need to push your app to in order to deploy it.

```
Creating app... done, ⬢ fakestuff-farboo-84560
https://fakestuff-farboo-84560.herokuapp.com/ | https://git.heroku.com/fakestuff-farboo-84560.git
```

## Set the Node Server Configuration

```
$ heroku config:set NPM_CONFIG_PRODUCTION=false
```

This command will tell Heroku to install the devDependencies. This enables Heroku to launch npm run build.

## Listen to the Host 0.0.0.0

```
$ heroku config:set HOST=0.0.0.0
```

## Run Node in Production Mode

```
heroku config:set NODE_ENV=production
```

## Tell Heroku to Run “npm run build"

Add "heroku-postbuild": "npm run build” to your "script" object in your package.json

```
"scripts": {
  "dev": "nuxt",
  "build": "nuxt build",
  "start": "nuxt start",
  "generate": "nuxt generate",
  "lint": "eslint --ext .js,.vue --ignore-path .gitignore .",
  "heroku-postbuild": "npm run build"
}
```

## Create a Procfile for Heroku

Heroku needs a Profile to execute and run our application. We just have to create a file with no extension at the root of our app folder, name it Procfile, and add the following line inside:

```
web: npm run start
```

## Push Your GitHub Repo to Heroku to Deploy

Finally all that’s left to do is stage, commit, and push our configured app to Heroku:

```
$ git add Procfile
$ git commit -a -m "Configuration to deploy to heroku"
$ git push heroku master
```

[refrance](https://medium.com/better-programming/deploy-your-app-for-free-in-7-easy-steps-thanks-to-heroku-dfd0f387edd0)
