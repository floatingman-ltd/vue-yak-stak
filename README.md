# vue-yak-stak

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Customize configuration

See [Vite Configuration Reference](https://vite.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

### Run End-to-End Tests with [Playwright](https://playwright.dev)

```sh
# Install browsers for the first run
npx playwright install

# When testing on CI, must build the project first
npm run build

# Runs the end-to-end tests
npm run test:e2e
# Runs the tests only on Chromium
npm run test:e2e -- --project=chromium
# Runs the tests of a specific file
npm run test:e2e -- tests/example.spec.ts
# Runs the tests in debug mode
npm run test:e2e -- --debug
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```

## How we got here

### Platform

Project setup:

```sh
npm create vue@latest
```

Selected options:

- Router
- Pinia
- Vitest
- End-to-End Testing
- ESLint
- Prettier

### VSCode

Extensions:

- [Debugger for Firefox](https://marketplace.visualstudio.com/items?itemName=firefox-devtools.vscode-firefox-debug)
- [Azure Static Web Apps](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azurestaticwebapps)
- [ESLint]()
- [Playwright Tewst for VSCode]()
- [Prettier]()
- [Pug Beautify]()
- [Vite](https://marketplace.visualstudio.com/items?itemName=antfu.vite)
- [Vitest]()
- [Vue - Offical]()
- [Vue Extension Box]()
- [Vue Peek]()
- []()
- []()

### Pug

Setup and config:

```sh
npm install --save pug
```

Add the following to the `eslint.config.json`:

```json
{
  "extends": ["plugin:vue/vue3-recommended", "plugin:vue-pug/vue3-recommended"]
}
```

Finally, we have a local and updated build of the `eslint-plugin-vue-pug` which we:

```sh
# go to the plugin project
cd ~/src/eslint-plugin-vue-pug
# create global link
npm link
# go tho this project
cd ~/src/vue-yak-stak
# import the link
npm link eslint-plugin-vue-pug
```
