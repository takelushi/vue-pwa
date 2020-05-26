# PWA on Vue

Progressive Web Application on Vue.js

## Requirements

```sh
# Node.js
node --version  # => v12.13.1

# npm
npm --version  # => 6.12.1
```

## Getting start

```sh
git clone git@github.com:takelushi/vue-pwa.git
cd vue-pwa
npm install

# Serve
npm run serve

# Build
npm run build

# Lint and fix
npm run lint
```

## Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).


## Deployment

* [Vue CLI: Deployment - GitHub Pages](https://cli.vuejs.org/guide/deployment.html#github-pages)

* Fix `vue.config.js`
  * Replace `vue-pwa` to your repository name.
* Deploy to GitHub Pages

   ```sh
   npm run build

   cd dist

   git init
   git add -A
   git commit -m 'deploy'

   git push -f git@github.com:<USER>/<REPO>.git master:gh-pages
   # e.g. git push -f git@github.com:takelushi/vue-pwa.git master:gh-pages
   ```
