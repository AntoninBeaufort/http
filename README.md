# 📦 HTTP Module

[![npm version][npm-version-src]][npm-version-href]
[![npm downloads][npm-downloads-src]][npm-downloads-href]
[![Circle CI][circle-ci-src]][circle-ci-href]
[![Codecov][codecov-src]][codecov-href]
[![Dependencies][david-dm-src]][david-dm-href]
[![Standard JS][standard-js-src]][standard-js-href]

TODO

## ✅ Features

✓ Automatically set base URL for client & server side

✓ Exposes `setToken` function to `$axios` so we can easily and globally set authentication tokens

✓ Automatically enables `withCredentials` when requesting to base URL

✓ Proxy request headers in SSR (Useful for auth)

✓ Integrated with Nuxt.js Progressbar while making requests (TODO)

✓ Integrated with [Proxy Module](https://github.com/nuxt-community/proxy-module)

✓ Auto retry requests

📖 [**Read Documentation**](https://http.nuxtjs.org) (TODO)

## Development

1. Clone this repository
2. Install dependencies using `yarn install` or `npm install`
3. Start development server using `npm run dev`

## 📑 License

[MIT License](./LICENSE)

Copyright (c) Nuxt.js Team

<!-- Badges -->
[npm-version-src]: https://img.shields.io/npm/dt/@nuxt/http.svg?style=flat-square
[npm-version-href]: https://npmjs.com/package/@nuxt/http
[npm-downloads-src]: https://img.shields.io/npm/v/@nuxt/http/latest.svg?style=flat-square
[npm-downloads-href]: https://npmjs.com/package/@nuxt/http
[circle-ci-src]: https://img.shields.io/circleci/project/github/nuxt/http-module.svg?style=flat-square
[circle-ci-href]: https://circleci.com/gh/nuxt/http-module
[codecov-src]: https://img.shields.io/codecov/c/github/nuxt/http-module.svg?style=flat-square
[codecov-href]: https://codecov.io/gh/nuxt/http-module
[david-dm-src]: https://david-dm.org/nuxt/http-module/status.svg?style=flat-square
[david-dm-href]: https://david-dm.org/nuxt/http-module
[standard-js-src]: https://img.shields.io/badge/code_style-standard-brightgreen.svg?style=flat-square
[standard-js-href]: https://standardjs.com
