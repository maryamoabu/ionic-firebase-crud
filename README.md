## Github Ionic
This is a sample Ionic 2 App that create,read,update and delete data from firebase database.

## Run the app
Make sure you have [nodejs](https://nodejs.org/en/) installed.

Install typecript
```bash
$ npm install -g typescript
```

Install Ionic CLI
```bash
$ npm install -g ionic
```

Install Cordova
```bash
$ npm install -g cordova
```

Clone this repo
```bash
$ git clonehttps://github.com/mtfaroks/ionic-firebase-crud.git
```

cd into the githubionic folder run npm install
```bash
$ npm install
```

After installing node modules you have to install firebase.

```bash
$ npm install firebase angularfire2 --save
```
this command add angularfire2 to your package.json file for your firebase database use.

You may need to restore the state of the ionic project, especially if you plan on using cordova.
```bash
ionic prepare
```

Build the app
```bash
$ npm run build
```

Serve the app
```bash
$ ionic serve
```

Head to `http://localhost:8100` in your browser and you'll see the app running
