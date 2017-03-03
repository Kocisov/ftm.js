# FTM
> console.time in class

## Usage
```js
// without transpiler
const ftm = require('ftm.js')

// with transpiler
import ftm from 'ftm.js'

const f = new ftm

f.define('test').startAll()
setTimeout(() => f.stop('test'), 2000)
```
