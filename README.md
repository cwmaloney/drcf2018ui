# DRCF UI

The is the DRCF 2018 UI.

## Setup

We use Firebase to host farmsteadlights.com.

### Install Firebase CLI

To install or update the Firebase CLI:

``` bash
npm install -g firebase-tools
firebase login
```

### Deploy to Firebase

``` bash
firebase deploy
```

## Build Setup

To install all dependencies from npm

``` bash
npm install
```

To run debug server with hot reload at localhost:3000

``` bash
npm run start
```

Deploy the build in the dist folder to Firebase:

``` bash
npm run deploy
```

See scripts in package.json for a full list of build and maintenance scripts.

## Runtime Dependencies

See "dependencies" in package.json for a complete list

1. Bootstrap
1. JQuery - required by Bootstrap
1. Popper - required by Bootstrap
1. Vue
1. VueRouter
1. Vuex

## Build Dependencies and Tools

TBD

## Visual Studio Code Setup

Install this extensions:

1. Debugger for Chrome
1. eslint
1. npm
1. Vetur

Useful optional extensions:

1. Beautify
1. Git History
1. markdownlint
1. vscode-icons

The project contains a tasks.json file that references the NPM tasks from the webpack config file.  See the Tasks menu.
The project contains a launch.json file that defines the debugging configuraiton.

## Debugging in Chrome

1. Open index.html in Chrome

## Debugging with Visual Studio Code

1. In VS Code, open the project folder (File/Open)
1. On the left navigation pane (Activity bar), click the debug icon
1. Choose Launch index.html as the debug configuration (next to the green arrow)
1. Click the green arrow icon in the debug view to open index.html with Chrome and attach the debugger

## FireBase notes

1. Install firebase-tools (see `firebase.google.com/docs/cli/`):

    ``` bash
    npm i -g firebase-tools
    ```

1. Login to FireBase:

   ``` bash
   firebase login
   ```

1. Test connection:

   ``` bash
   firebase list
   ```

1. Initialize the connect to the Firebase project:

   ``` bash
   firebase init
   ```

1. Deploy app to firebase:

   ``` bash
   firebase deploy
   ```

## npm Notes

1. List globally install packages

  ``` bash
  npm list -g --depth 0
  ````

1. List localy installed packages

  ``` bash
  npm list --depth 0
  ````

1. Update packages to latest version available

Install npm-check-updates

  ``` bash
  npm install -g npm-check-updates
  ````

Check local packages

  ``` bash
  ncu
  ````

Check global packages

  ``` bash
  ncu -g
  ````

1. Node version manager

  ``` bash
  npm i n
  ````

  ``` bash
  n
  ````
