## Basic ES6 Scaffolding

A basic es2015(Ecmascript 6) scaffolding with browserify and gulp. This scaffolding has a yeoman generator: https://github.com/iranreyes/generator-ecma-six

### Initial setup

```bash
# Clone the repo...
git clone https://github.com/iranreyes/basic-es6-scaffolding.git
cd basic-es6-scaffolding

# Then, you need to install all the dependencies...
npm install

# If you wanna be able to use global command `gulp`...
npm install -g gulp
```

### Running in the browser

This scaffolding includes `browser-sync` to init a server and is watching the change in your javascript files.

```bash
# Init the server and start watching the files
gulp serve
```