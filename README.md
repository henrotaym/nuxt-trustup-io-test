# nuxt-trustup-io-test

[![npm version][npm-version-src]][npm-version-href]
[![npm downloads][npm-downloads-src]][npm-downloads-href]
[![License][license-src]][license-href]
[![Nuxt][nuxt-src]][nuxt-href]

test

- [✨ &nbsp;Release Notes](/CHANGELOG.md)
<!-- - [🏀 Online playground](https://stackblitz.com/github/your-org/@henrotaym/nuxt-trustup-io-test?file=playground%2Fapp.vue) -->
<!-- - [📖 &nbsp;Documentation](https://example.com) -->

## Features

<!-- Highlight some of the features your module provide here -->
- ⛰ &nbsp;Foo
- 🚠 &nbsp;Bar
- 🌲 &nbsp;Baz

## Quick Setup

1. Add `@henrotaym/nuxt-trustup-io-test` dependency to your project

```bash
# Using pnpm
pnpm add -D @henrotaym/nuxt-trustup-io-test

# Using yarn
yarn add --dev @henrotaym/nuxt-trustup-io-test

# Using npm
npm install --save-dev @henrotaym/nuxt-trustup-io-test
```

2. Add `@henrotaym/nuxt-trustup-io-test` to the `modules` section of `nuxt.config.ts`

```js
export default defineNuxtConfig({
  modules: [
    '@henrotaym/nuxt-trustup-io-test'
  ],
  trustupIoTest: {}
})
```

That's it! You can now use nuxt-trustup-io-test in your Nuxt app ✨

## Development

### Bootstrap module
Find and replace all on all files (CMD+SHIFT+F):
```shell
  - nuxt-trustup-io-test // nuxt-trustup-io-toasteo
  - test // Our notification package for nuxt.
  - trustupIoTest // trustupIoToasteo
  - @henrotaym // @deegital
  - git@github.com:henrotaym/nuxt-trustup-io-test.git // git@github.com:deegitalbe/nuxt-trustup-io-toasteo.git
```
Start bootstrap script
```shell
./cli bootstrap
```

### Available commands
```bash
# Install dependencies
./cli yarn install

# Generate playground
./cli yarn generate

# Start project
./cli start

# Stop project
./cli start

# Build the playground for production
./cli yarn dev:build

# Run ESLint
./cli yarn lint

# Run Vitest
./cli yarn test
./cli yarn test:watch

# Validate your package (running linter & typecript validation)
./cli yarn check

# Build the package for publication
./cli yarn build

# Release new version
npm version patch
```

<!-- Badges -->
[npm-version-src]: https://img.shields.io/npm/v/@henrotaym/nuxt-trustup-io-test/latest.svg?style=flat&colorA=18181B&colorB=28CF8D
[npm-version-href]: https://npmjs.com/package/@henrotaym/nuxt-trustup-io-test

[npm-downloads-src]: https://img.shields.io/npm/dm/@henrotaym/nuxt-trustup-io-test.svg?style=flat&colorA=18181B&colorB=28CF8D
[npm-downloads-href]: https://npmjs.com/package/@henrotaym/nuxt-trustup-io-test

[license-src]: https://img.shields.io/npm/l/@henrotaym/nuxt-trustup-io-test.svg?style=flat&colorA=18181B&colorB=28CF8D
[license-href]: https://npmjs.com/package/@henrotaym/nuxt-trustup-io-test

[nuxt-src]: https://img.shields.io/badge/Nuxt-18181B?logo=nuxt.js
[nuxt-href]: https://nuxt.com
