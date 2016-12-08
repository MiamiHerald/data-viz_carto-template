# Data-Viz: Carto Map Starter

## About

This template will serve as a starting point for embedded data visualization projects for the Miami Herald using [Carto](https://carto.com/).

## Installation

Based off of [Gulp Starter](https://github.com/vigetlabs/gulp-starter).

Extra additions include:
- [Bourbon](http://bourbon.io/) and [Bourbon Neat](http://neat.bourbon.io/)
- [jQuery](https://jquery.com/)
- [pym.js](http://blog.apps.npr.org/pym.js/)

```
git clone https://github.com/MiamiHerald/data-viz_carto-template.git MyApp
cd MyApp
npm install
```

### Note about Node

If you get an error within `./src/javascripts/app.js`, then you need to switch your Node version to `5.12.0` or earlier using [nvm](https://github.com/creationix/nvm) and run `npm rebuild node-sass` as there is an issue with Node 6+. See [#302](https://github.com/vigetlabs/gulp-starter/issues/302).

To remove git and add start your own repo run `rm -rf .git && git init`

### Serving

`npm start`

Your browser should open with [http://localhost:3000](http://localhost:3000), browsersync should be active and you should be ready to go :rocket:.

### Help

email: cwilliams at miamiherald dot com :thumbsup:
