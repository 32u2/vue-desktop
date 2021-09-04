# About

- Vue UI is in the **app** folder
- app\vue.config.js routes Vue production build to **resources** folder
- **astilectron-bundler** command places final output to the **output** folder

# Example

```
cd app
npm run build
cd ..
astilectron-bundler
```

# Fresh Vue install

This repo uses Vue3, babel, router, vuex and eslint. If you wish to replace this starter with a different Vue preset, place fresh Vue install in the **app** folder and add app\vue.config.js file with the following content:

```
module.exports = {
    outputDir: '../resources/app/',
    publicPath: './',
}
```

# Credits

- [astilectron](https://github.com/asticode/go-astilectron)
- [Vue](https://vuejs.org)

