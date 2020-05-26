# Guide

## Install requirements

* Node.js
* npm
* Vue CLI

   ```sh
   npm install -g @vue/cli
   vue --verison  # => @vue/cli 4.3.1
   ```

## Create Vue project

```sh
vue create vue-pwa

# ? Please pick a preset: Manually select features

# ? Check the features needed for your project: TS, PWA, Router, CSS Pre-processors, Linter

# ? Use class-style component syntax?: Yes

# ? Use Babel alongside TypeScript (required for modern mode, auto-detected polyfills, transpiling JSX)?: No

# ? Use history mode for router? (Requires proper server setup for index fallback in production): Yes

# ? Pick a CSS pre-processor (PostCSS, Autoprefixer and CSS Modules are supported by default): Stylus

# ? Pick a linter / formatter config: Prettier

# ? Pick additional lint features: Lint on save

# ? Where do you prefer placing config for Babel, ESLint, etc.? In dedicated config files

# ? Save this as a preset for future projects? No

# ? Pick the package manager to use when installing dependencies: NPM
```

## Setup for deployment

* Create `vue.config.js`
