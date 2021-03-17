# Battleships
This project is a basic [Vue.js](https://vuejs.org/) example application based on the famous game Battleships. It was generated with [Vue CLI](https://cli.vuejs.org/) version 2.9.6 and [BootstrapVue](https://bootstrap-vue.org/).

## [Demo](http://ng-battleships.gearhostpreview.com/vue/)

## Game
### Make it run
- clone the repo and install npm packages
- build the project and serve on development server

### Game Start

- When the browser opens, a new game starts automatically
- Start a new game by using the menu on the player's board
- All ships are placed automatically

### Play the Game 

Player clicks on the coordinates in the Opponent's board to fire at the enemy. After that, the opponent strikes back. Hits and misses are marked by a "x" on the coordinate (miss = white, hit red)
- Player wins, when all Opponent's ships are sunk
- Player looses, when his ships are sunk

### KI

Don't complain - there is no KI. The opponent just fires randomly at your coordinates. It's just a showcase game ;-)


## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
