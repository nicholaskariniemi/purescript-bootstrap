# PureScript bootstrap project

This is a bootstrap project for developing web apps with PureScript. It is a simple server written in PureScript that serves a single static page running PureScript client code. Source files are rebuilt and the server is restarted when source code changes.

Tech stack: npm + bower + gulp + browserify + express

## Install external dependencies

* [PureScript](http://www.purescript.org/download/)
* [Node Package Manager](https://nodejs.org/)

## Install project dependencies

```
npm install
./bower.sh update
```

## Build and run project

```
./gulp.sh
```