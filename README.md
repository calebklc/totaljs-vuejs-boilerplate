# Total.js + Vue.js Boilerplate (No SSR) 

Using Vue components in Total.js' views

## Dependencies
* Total.js 2.x.x
* Vue.js 2.x.x

## Installation
1. Install totaljs globally because the build.js will be minified using Total.js minify command
```bash
npm install -g total.js
```

2. Install dependencies
```bash
npm install
# or
yarn
```

## How to use
1. For development mode
```bash
# Complie Vue components
npm run client:dev

# Run Total.js in development mode
node debug.js
```

2. For production mode
```bash
# Complie Vue components
npm run client:prod

# Run Total.js in production mode
node release.js
```
