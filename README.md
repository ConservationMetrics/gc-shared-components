# GuardianConnector Shared Resources Library

[![npm version][npm-version-src]][npm-version-href]
[![npm downloads][npm-downloads-src]][npm-downloads-href]
[![License][license-src]][license-href]
[![Nuxt][nuxt-src]][nuxt-href]

Shared components (components, pages, assets, middleware and more) for GuardianConnector Nuxt.js applications.

- [✨ &nbsp;Release Notes](/CHANGELOG.md)

## Quick Setup

Install the module to your Nuxt application with one command:

```bash
npx nuxi module add gc-shared-resources
```

That's it! You can now use GuardianConnector Shared Resources Library in your Nuxt app ✨

## How to use this module

Unlike many Nuxt modules, this repository does not use a `playground/` directory. Instead, this module should be used directly with a GuardianConnector Nuxt application.

For development purposes, utilize a symlink to this module in a Nuxt application to use your local code in runtime:

1. Generate type stubs by running `npm run dev:prepare`
2. In your Nuxt application, run `npm link ../gc-shared-components` (assuming your module and Nuxt application are in the same root directory, if not adapt the path)

## Contribution

<details>
  <summary>Local development</summary>
  
  ```bash
  # Install dependencies
  npm install
  
  # Generate type stubs
  npm run dev:prepare
  
  # Develop with the playground
  npm run dev
  
  # Build the playground
  npm run dev:build
  
  # Create a npm symlink
  npm run link
  
  # Run Prettier
  npm run lint
  
  # Run Vitest
  npm run test
  npm run test:watch
  
  # Release new version
  npm run release
  ```

</details>

<!-- Badges -->

[npm-version-src]: https://img.shields.io/npm/v/gc-shared-resources/latest.svg?style=flat&colorA=020420&colorB=00DC82
[npm-version-href]: https://npmjs.com/package/gc-shared-resources
[npm-downloads-src]: https://img.shields.io/npm/dm/gc-shared-resources.svg?style=flat&colorA=020420&colorB=00DC82
[npm-downloads-href]: https://npmjs.com/package/gc-shared-resources
[license-src]: https://img.shields.io/npm/l/gc-shared-resources.svg?style=flat&colorA=020420&colorB=00DC82
[license-href]: https://npmjs.com/package/gc-shared-resources
[nuxt-src]: https://img.shields.io/badge/Nuxt-020420?logo=nuxt.js
[nuxt-href]: https://nuxt.com
