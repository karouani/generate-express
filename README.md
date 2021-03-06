![generate-express logo](assets/generate-express-small.png)

## Generate an Express app from the command line

#### Heavily inspired by
[Express'](https://www.npmjs.com/package/express) application generator.

![but wait theres more](assets/waitTheresMore.gif "So much more...")

## Features
* ES6+ support (including import/export) with latest babel support
* Interactive CLI prompts to customize your build (no more flags)
* Choose your own database starter configs (`mongojs`, `mongo + mongoose`, `sequelize`, or `none`)
* Api-only option to exclude views and public directory, or pick from one of the original view engines offered by express-generator
* File watcher via `nodemon` to transpile code on change 

### Coming soon
* More database configs, including dynamodb and aurora
* Deprecating less popular view engines
* More CLI options for more packages
* Testing: starting with `jest` will add configs for other frameworks eventually
* More testing of this framework itself

## Quick Start
```sh
npx generate-express myCoolProject
```
You can download [npx here](https://www.npmjs.com/package/npx) by running `npm i -g npx`


### Install dependencies:

```sh
$ cd myCoolProject
$ npm install
```

### Start your Express.js
```sh
# run with file watch (development)
$ npm run start
```
#### Default routes
```
localhost:3001/api
localhost:3001/api/users
```

### Other `npm` scripts
```sh
# run with file watch (development)
$ npm run start

# run as production
$ npm run prod

# create prod build to /dist
$ npm run build
```

## Contributions
Feel free to raise an issue or create a Pull Request if you see ways that can improve this library.

### Current Contributors
[![](https://sourcerer.io/fame/smaharj1/eklemen/generate-express/images/0)](https://sourcerer.io/fame/smaharj1/eklemen/generate-express/links/0)[![](https://sourcerer.io/fame/smaharj1/eklemen/generate-express/images/1)](https://sourcerer.io/fame/smaharj1/eklemen/generate-express/links/1)[![](https://sourcerer.io/fame/smaharj1/eklemen/generate-express/images/2)](https://sourcerer.io/fame/smaharj1/eklemen/generate-express/links/2)[![](https://sourcerer.io/fame/smaharj1/eklemen/generate-express/images/3)](https://sourcerer.io/fame/smaharj1/eklemen/generate-express/links/3)[![](https://sourcerer.io/fame/smaharj1/eklemen/generate-express/images/4)](https://sourcerer.io/fame/smaharj1/eklemen/generate-express/links/4)[![](https://sourcerer.io/fame/smaharj1/eklemen/generate-express/images/5)](https://sourcerer.io/fame/smaharj1/eklemen/generate-express/links/5)[![](https://sourcerer.io/fame/smaharj1/eklemen/generate-express/images/6)](https://sourcerer.io/fame/smaharj1/eklemen/generate-express/links/6)[![](https://sourcerer.io/fame/smaharj1/eklemen/generate-express/images/7)](https://sourcerer.io/fame/smaharj1/eklemen/generate-express/links/7)

## License

[MIT](LICENSE)
