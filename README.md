# yuki-createjs
⛩  yuki-createjs

## Libs
 - easeljs-0.8.2.combined.js
 - preloadjs-0.6.2.combined.js
 - soundjs-0.6.2.combined.js
 - tweenjs-0.6.2.combined.js

## Install
```bash
$ yarn add yuki-createjs
# or
$ npm install yuki-createjs --save
```

## Usage

### Include all
```js
import 'yuki-createjs'
// or
require('yuki-createjs')

// then
console.log(createjs) // <- Global 🍻
```

### Just one
```js
import 'yuki-createjs/lib/preloadjs-0.6.2.combined'
// or
require('yuki-createjs/lib/preloadjs-0.6.2.combined')

// then 🍻
var preload = new createjs.LoadQueue()
```
