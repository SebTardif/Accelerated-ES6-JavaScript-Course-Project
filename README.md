# Accelerated-ES6-JavaScript-Course-Project
 Accelerated ES6 JavaScript Course Project: local development setup with babel and webpack

# Attribution:

This project was forked from https://github.com/wbkd/webpack-starter


### Installation

```
npm install
```

### Start Dev Server

```
npm run dev
```

### Build Prod Version

```
npm run build
```

### Features:

* ES6 Support via [babel-loader](https://github.com/babel/babel-loader)
* SASS Support via [sass-loader](https://github.com/jtangelder/sass-loader)
* Linting via [eslint-loader](https://github.com/MoOx/eslint-loader)

When running `npm run build` the [extract-text-webpack-plugin](https://github.com/webpack/extract-text-webpack-plugin) is used to move the css to a separate file and included in the head of the `index.html`, so that the styles are applied before any javascript gets loaded. This function is disabled for the dev version, because the loader doesn't support hot module replacement.
