# About this starter

This starter yields single executable desktop application that can be (cross)compiled for Windows, Linux and OSX.

- Vue UI is in the **app** folder
- app\vue.config.js routes Vue production build to **resources** folder
- **astilectron-bundler** command places final output to the **output** folder

# Installation

You will need:

- working Go installation
- enabled Go modules (set GO111MODULE=on)

For convenience, only **node_modules** are .gitignored, but not vendored Go libraries.

```
cd app
npm install
npm run build
cd ..
astilectron-bundler
```

# Screenshot

![vue-desktop](screenshot.png?raw=true "vue-desktop")

# Fresh Vue install

This repo uses Vue3, babel, router, vuex and eslint. If you wish to replace this UI starter with a different Vue preset, place fresh Vue install in the **app** folder and add app\vue.config.js file with the following content:

```
module.exports = {
    outputDir: '../resources/app/',
    publicPath: './',
}
```

# Credits

- [astilectron](https://github.com/asticode/go-astilectron)
- [Vue](https://vuejs.org)

