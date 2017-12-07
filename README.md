# React Component Library Playground for Meeact

### OVERIVEW
This is a playground for experimenting with a component library. This is intended to provide:

* a small app to experiment with a component library locally.
* a lightweight webpack config (for development and production)
* some helpful tooling for development workflow
* a similar setup to what you'll see in the wild

_*NOTE:* This app is based on Alan Smith's [React + Node Starter](https://github.com/alanbsmith/react-node-example)._


### Link to your library

Since this project was meant to be tested with `meeact-comp`, do the following:

1. Go to root of `meeact-comp` and run `npm link`
2. Go to root of this repo and run `npm link meeact-comp`
We are ready to use our component library in the playground!

### UP & RUNNING
* Install dependencies
`$ npm install` or `$ yarn`

* Fire up a development server:
* `$ npm run dev`

Once the server is running, you can visit `http://localhost:8080/`


### Linting
_This assumes you have eslint and eslint-watch installed. If you don't, run the following:_
```
$ npm i -g eslint eslint-watch
```
or if you need permissions:
```
$ sudo npm i -g eslint eslint-watch
```

To run the linter once:
```
$ npm run lint
```

To run the watch task:
```
$ npm run lint:watch
```

### Testing

To run the tests:
```
$ npm test
```

### Production Build

To build your production assets and run the server:
```
$ npm start
```

