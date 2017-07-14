# bundle-buddy-webpack-plugin
[![npm](https://badge.fury.io/js/bundle-buddy-webpack-plugin.svg)](https://badge.fury.io/js/bundle-buddy-webpack-plugin)
![](https://david-dm.org/TheLarkInn/bundle-buddy-webpack-plugin.svg)

Your favorite [bundle-buddy](https://github.com/samccone/bundle-buddy) duplication analyzer, made as a webpack plugin.

## Installation

### Yarn

```bash
yarn add bundle-buddy-webpack-plugin --dev
```

### npm

```bash
npm install bundle-buddy-webpack-plugin --save-dev
```

## Usage
Just require the plugin into your webpack configuration, and pass it to the `plugins` array.

**webpack.config.js**

```javascript
const BundleBuddyWebpackPlugin = require("bundle-buddy-webpack-plugin");

module.exports = {
  // ...
  plugins: [
    new BundleBuddyWebpackPlugin({sam: true})
  ]

};
```

### Options
Currently there are no options yet!!! However, please feel free to submit an issue or PR!!!!!

### Bugs
If you believe there is an issue with the plugin itself, by all mean submit an issue!!! However this directly uses [bundle-buddy](https://github.com/samccone/bundle-buddy) and I would also verify that it is not an issue reported there first.