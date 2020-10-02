# class-loader

## install

```
npm install class-loader
```

## how to use

```
const classLoader = require('class-loader')
const path = require('path')

const service = classLoader(path.join(__dirname, '/app/service'))

// options
const service = classLoader(path.join(__dirname, '/app/service'), { ignore: 'index.js' })
```
