# Awesome Micro with stars

[<img align="right" src="https://camo.githubusercontent.com/67335088cb7b156fb779f6d60635e70780efe714/68747470733a2f2f636c6475702e636f6d2f4a446d6d4858337568462e737667" />](https://github.com/vercel/micro) ⭐ 10,625 | 🐛 8 | 🌐 TypeScript | 📅 2026-05-21

> A collection of awesome things regarding Vercel's [Micro](https://github.com/zeit/micro) ⭐ 10,625 | 🐛 8 | 🌐 TypeScript | 📅 2026-05-21 — Asynchronous HTTP microservices.

## Contents

* [Modules](#modules)
  * [Routing](#routing)
  * [Authentication](#authentication)
  * [Analytics](#analytics)
  * [Loggers, Errors & Reporting](#loggers-errors--reporting)
  * [Middlewares](#middlewares)
  * [Wrappers](#wrappers)
  * [HTTP Requests](#http-requests)
  * [Higher Order](#higher-order)
  * [Utilities](#utilities)
* [Deployment Tools](#deployment-tools)
* [Development Tools](#development-tools)
* [Boilerplates](#boilerplates)
* [Articles & FAQ](#articles--faq)
* [Built with Micro](#built-with-micro)

## Modules

### Routing

* [micro-router](https://github.com/pedronauck/micro-router) ⭐ 613 | 🐛 21 | 🌐 JavaScript | 📅 2022-12-07 - A tiny and functional router for Zeit's Micro.
* [router](https://github.com/pillarjs/router) ⭐ 448 | 🐛 51 | 🌐 JavaScript | 📅 2026-06-02 - Simple middleware-style router.
* [fs-router](https://github.com/jesseditson/fs-router) ⭐ 164 | 🐛 12 | 🌐 JavaScript | 📅 2022-12-09 - Use the FS as your micro router.
* [micro-fork](https://github.com/amio/micro-fork) ⭐ 95 | 🐛 6 | 🌐 JavaScript | 📅 2023-02-21 - A fast and functional router for ZEIT's Micro.
* [micro-route](https://github.com/dotcypress/micro-route) ⭐ 94 | 🐛 0 | 🌐 JavaScript | 📅 2017-11-16 - Tiny http routing helper.
* [micro-http-router](https://github.com/protocol114/micro-http-router) ⭐ 24 | 🐛 0 | 🌐 JavaScript | 📅 2019-05-21 - Express-like router built with a radix tree for lightning-fast performance.
* [micro-ex-router](https://github.com/Masquerade-Circus/micro-ex-router) ⭐ 21 | 🐛 11 | 🌐 JavaScript | 📅 2023-01-06 - Express style router for Zeit's Micro.
* [micro-method-router](https://github.com/jamo/micro-method-router) ⭐ 11 | 🐛 2 | 🌐 JavaScript | 📅 2019-07-10 - Minimal routing layer for HTTP methods.
* [@synvox/router](https://github.com/Synvox/router) ⚠️ Archived - A tiny routing library inspired by react hooks and express.js.
* [micro-action](https://github.com/zhaoyao91/micro-action) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2017-07-18 - Define actions for Zeit's Micro using micro-action protocol.
* [@bessonovs/node-http-router](https://github.com/Bessonov/node-http-router) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2024-05-14 - An extensible TypeScript router for micro and Node.js.

### Authentication

* [microauth](https://github.com/microauth) - Collection of authentication modules for ▲zeit's micro.
  * [microauth-twitter](https://github.com/microauth/microauth-twitter) ⭐ 39 | 🐛 3 | 🌐 JavaScript | 📅 2020-06-03
  * [microauth-facebook](https://github.com/microauth/microauth-facebook) ⭐ 16 | 🐛 14 | 🌐 JavaScript | 📅 2026-01-27
  * [microauth-google](https://github.com/microauth/microauth-google) ⭐ 11 | 🐛 1 | 🌐 JavaScript | 📅 2020-02-05
  * [microauth-github](https://github.com/microauth/microauth-github) ⭐ 8 | 🐛 16 | 🌐 JavaScript | 📅 2026-01-22
  * [microauth-slack](https://github.com/microauth/microauth-slack) ⭐ 8 | 🐛 14 | 🌐 JavaScript | 📅 2026-01-24

### Analytics

* [micro-analytics](https://github.com/mxstbr/micro-analytics) ⭐ 733 | 🐛 17 | 🌐 JavaScript | 📅 2018-07-16 - Public analytics as a Node.js microservice, no sysadmin experience required.
* [micro-stats](https://github.com/dotcypress/micro-stats) ⭐ 12 | 🐛 0 | 🌐 JavaScript | 📅 2018-06-11 - Statsd helper for Micro.

### Loggers, Errors & Reporting

* [micro-sentry](https://github.com/tanmulabs/micro-sentry) ⭐ 34 | 🐛 10 | 🌐 JavaScript | 📅 2023-01-06 - Send micro errors to the Sentry service.
* [micro-notify](https://github.com/pauldariye/micro-notify) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2019-08-06 - A simple [.notify](https://github.com/bugsnag/bugsnag-js) ⭐ 894 | 🐛 84 | 🌐 TypeScript | 📅 2026-08-25 wrapper to send micro errors to Bugsnag.
* [micro-morgan](https://github.com/nickcis/micro-morgan) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2019-03-21 - [Morgan](https://github.com/expressjs/morgan) ⭐ 8,201 | 🐛 30 | 🌐 JavaScript | 📅 2026-08-20 HTTP request logger middleware for Zeit's Micro framework.

### Middlewares

* [micro-cors](https://github.com/possibilities/micro-cors) ⭐ 197 | 🐛 13 | 🌐 JavaScript | 📅 2022-12-07 - Simple CORS middleware.
* [micro-ratelimit](https://github.com/dotcypress/micro-ratelimit) ⭐ 74 | 🐛 1 | 🌐 JavaScript | 📅 2018-10-04 - Rate limiting middleware for Micro.
* [micro-mw](https://github.com/mhamann/micro-mw) ⭐ 20 | 🐛 9 | 🌐 JavaScript | 📅 2023-01-03 - A simple library for abstracting middleware away from ZEIT Micro routes / functions.
* [micro-ajv](https://github.com/igat64/micro-ajv) ⭐ 5 | 🐛 12 | 🌐 JavaScript | 📅 2023-01-03 - An Ajv (Another JSON Schema Validator) middleware for Micro.
* [micro-csrf](https://github.com/fourcube/micro-csrf) ⭐ 3 | 🐛 8 | 🌐 TypeScript | 📅 2023-01-05 - Anti-CSRF middleware.
* [micro-logzio](https://github.com/littledumb/micro-logzio) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2018-11-19 - A middleware for micro framework that logs requests and responses using logz.io service.
* [micro-nosniff](https://github.com/GaiAma/micro-nosniff) ⭐ 1 | 🐛 4 | 🌐 TypeScript | 📅 2023-03-03 - Prevents mime type sniffing

### Wrappers

* [micro-jwt-auth](https://github.com/kandros/micro-jwt-auth) ⚠️ Archived - Json web token(jwt) authorization wrapper for Micro.
* [micro-joi](https://github.com/stearm/micro-joi) ⚠️ Archived - Joi wrapper for Micro.
* [micro-boom](https://github.com/onbjerg/micro-boom) ⚠️ Archived - Wraps errors in micro with Boom.
* [micro-upload](https://github.com/julianduque/micro-upload) ⭐ 34 | 🐛 3 | 🌐 JavaScript | 📅 2020-08-05 - A express-fileupload wrapper for Zeit's micro.
* [micro-superstruct](https://github.com/brandon93s/micro-superstruct) ⭐ 16 | 🐛 0 | 🌐 JavaScript | 📅 2020-09-07 - Superstruct wrapper for Micro enabling validation of request body and query parameters.
* [micro-notify](https://github.com/pauldariye/micro-notify) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2019-08-06 - A simple [.notify](https://github.com/bugsnag/bugsnag-js) ⭐ 894 | 🐛 84 | 🌐 TypeScript | 📅 2026-08-25 wrapper to send micro errors to Bugsnag.

### HTTP Requests

* [micro-chain](https://github.com/dimapaloskin/micro-chain) ⭐ 24 | 🐛 10 | 🌐 JavaScript | 📅 2020-06-03 - Builds flexible requests chains and pass them into micro handler.
* [micro-redirect](https://github.com/timReynolds/micro-redirect) ⭐ 13 | 🐛 12 | 🌐 JavaScript | 📅 2023-01-09 - A redirect function for Zeit's micro.
* [micro-correlation-id](https://github.com/tafarij/micro-correlation-id) ⭐ 10 | 🐛 1 | 🌐 JavaScript | 📅 2023-10-17 - Correlate http requests across microservices.
* [micro-get](https://github.com/romuloalves/micro-get) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2024-04-27 - Only accepts GET request for microservices built with Micro.
* [micro-post](https://github.com/romuloalves/micro-post) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2024-04-27 - Only accepts POST request for microservices built with Micro.
* [micro-protocol](https://github.com/cprecioso/micro-protocol) ⚠️ Archived - Get the protocol of the request (optionally following proxies).
* [micro-host](https://github.com/cprecioso/micro-host) ⚠️ Archived - Get the host of the request (optionally following proxies).
* [micro-hostname](https://github.com/cprecioso/micro-hostname) ⚠️ Archived - Get the hostname (host without port) of the request (optionally following proxies)
* [micro-bunyan-request](https://github.com/maximeshr/micro-bunyan-request) - Request, response logger middleware using bunyan for micro framework.

### Higher Order

* [micro-compose](https://github.com/microauth/micro-compose) ⭐ 24 | 🐛 3 | 🌐 JavaScript | 📅 2020-06-03 - Higher-order "compose" function.
* [micro-hoofs](https://github.com/KaleoSoftware/micro-hoofs) - Higher-order functions for zeit/micro.

### Utilities

* [serve-handler](https://github.com/zeit/serve-handler) ⭐ 618 | 🐛 86 | 🌐 JavaScript | 📅 2026-05-04 - Static file serving and directory listing handler, used by [Serve](https://github.com/zeit/serve) ⭐ 9,896 | 🐛 149 | 🌐 TypeScript | 📅 2026-06-30
* [micro-compress](https://github.com/joakimbeng/micro-compress) ⭐ 43 | 🐛 1 | 🌐 JavaScript | 📅 2017-01-27 - Compression for HTTP microservices.
* [micro-cacheable](https://github.com/fmiras/micro-cacheable) ⭐ 36 | 🐛 5 | 🌐 JavaScript | 📅 2020-03-24 - A micro utility for data caching
* [micro-match](https://github.com/nblackburn/micro-match) ⚠️ Archived -  A simple url matching utility for micro.
* [micro-chain](https://github.com/dimapaloskin/micro-chain) ⭐ 24 | 🐛 10 | 🌐 JavaScript | 📅 2020-06-03 - Builds flexible requests chains and pass them into micro handler.
* [micro-health](https://github.com/fmiras/micro-health) ⭐ 20 | 🐛 1 | 🌐 JavaScript | 📅 2020-03-24 - An extension of micro with a Health Check API
* [micro-cookie-session](https://github.com/billymoon/micro-cookie-session) ⭐ 16 | 🐛 0 | 🌐 JavaScript | 📅 2019-03-09 - Simple cookie-based session storage for micro.
* [micronize](https://github.com/nickcis/micronize) ⭐ 8 | 🐛 0 | 🌐 JavaScript | 📅 2019-03-21 - Simple way of enhacing a function with Zeit's Micro framework (usefull for serverless environment, ie: now & aws lambda).
* [micro-helmet](https://github.com/goto-bus-stop/micro-helmet) ⭐ 5 | 🐛 3 | 🌐 JavaScript | 📅 2026-05-22 - Security headers for micro, using the popular [Helmet](https://www.npmjs.com/package/helmet) module
* [micro-cookie](https://github.com/zakjholt/micro-cookie) ⭐ 3 | 🐛 1 | 🌐 JavaScript | 📅 2026-04-08 - Cookie parsing for Zeit's Micro.
* [micro-query](https://github.com/nerdify/micro-query) - Simple querystring parser for Zeit's Micro.

## Deployment Tools

* [aws-serverless-micro](https://github.com/nathancahill/aws-serverless-micro) ⭐ 14 | 🐛 7 | 🌐 JavaScript | 📅 2023-01-05 - Deploy Micro functions on AWS Lambda

## Development Tools

* [micro-dev](https://github.com/zeit/micro-dev) ⭐ 711 | 🐛 29 | 🌐 JavaScript | 📅 2024-06-08 - The development environment for `micro`.
* [micro-visualize](https://github.com/onbjerg/micro-visualize) ⚠️ Archived - Development tool that visualizes requests and responses for services written with Micro.
* [dev-gateway](https://github.com/dimapaloskin/dev-gateway) ⭐ 32 | 🐛 14 | 🌐 JavaScript | 📅 2020-06-03 - Local development gateway with [path aliases](https://zeit.co/docs/features/path-aliases) support.
* [serve-micro-cluster](https://github.com/tylersnyder/serve-micro-cluster) ⭐ 19 | 🐛 0 | 🌐 JavaScript | 📅 2017-04-13 - It's like Path Alias on now, but for local development.
* [micro-proxy](https://github.com/zeit/micro-proxy) - Run multiple micro servers and a front proxy at a time.
* [instantapi](https://github.com/martinstarman/instantapi) - Local instant development api.

## Boilerplates

* [micro-graphql](https://github.com/hyperfuse/micro-graphql) ⭐ 146 | 🐛 0 | 🌐 JavaScript | 📅 2017-01-20 - GraphQL Microservice
* [generator-micro-service](https://github.com/vadimdemedes/generator-micro-service) ⭐ 144 | 🐛 1 | 🌐 JavaScript | 📅 2017-04-07 - Yeoman generator to kick-start your microservice with `micro` and `ava`
* [micro-authentication-starter](https://github.com/littleStudent/micro-authentication-starter) ⭐ 97 | 🐛 0 | 🌐 JavaScript | 📅 2018-04-25 - Starter kit with built in authentication using bcrypt and jsonwebtokens
* [nuxt-micro](https://github.com/nuxt-community/micro-template) ⭐ 73 | 🐛 2 | 🌐 JavaScript | 📅 2020-12-11 - A [Vue-CLI](https://github.com/vuejs/vue-cli) ⭐ 29,543 | 🐛 1,070 | 🌐 JavaScript | 📅 2025-08-21 template to generate a [Nuxt.js](https://github.com/nuxt/nuxt.js) ⭐ 60,802 | 🐛 543 | 🌐 TypeScript | 📅 2026-08-26 project with micro as a backend
* [create-micro](https://github.com/romuloalves/create-micro) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2024-04-27 - a generator for `micro` projects

## Articles & FAQ

* [Regarding no-middleware](https://github.com/vercel/micro/issues/8) ⭐ 10,625 | 🐛 8 | 🌐 TypeScript | 📅 2026-05-21
* [Use Micro with routes](https://github.com/vercel/micro/issues/16#issuecomment-193518395) ⭐ 10,625 | 🐛 8 | 🌐 TypeScript | 📅 2026-05-21
* [Difference between Micro and Koa](https://github.com/vercel/micro/issues/309#issuecomment-332503863) ⭐ 10,625 | 🐛 8 | 🌐 TypeScript | 📅 2026-05-21
* [Minimum Viable Async with Node 6](https://gist.github.com/rauchg/8199de60db48026a6670620a1c33b700)

## Built with Micro

* [Serve](https://github.com/vercel/serve) ⭐ 9,896 | 🐛 149 | 🌐 TypeScript | 📅 2026-06-30 - Static file serving and directory listing
* [micro-github](https://github.com/mxstbr/micro-github) ⭐ 721 | 🐛 3 | 🌐 JavaScript | 📅 2019-10-11 - Add authentication with GitHub to your application
* [gh-latest-repos](https://github.com/sindresorhus/gh-latest-repos) ⭐ 151 | 🐛 0 | 🌐 JavaScript | 📅 2024-04-30 - Get the latest public GitHub repos from a user
* [micro-jaymock](https://github.com/Meeshkan/micro-jaymock) ⚠️ Archived - Tiny API mocking microservice for generating fake JSON data
* [imagemin-micro](https://github.com/imagemin/imagemin-micro) ⭐ 60 | 🐛 0 | 🌐 JavaScript | 📅 2021-05-29 - Minify images
* [micro-gallery](https://github.com/andreasmcdermott/micro-gallery) ⭐ 36 | 🐛 0 | 🌐 JavaScript | 📅 2018-02-04 - Like Vercel's serve, but for images.
* [font-mess](https://github.com/amio/font-mess) ⭐ 33 | 🐛 0 | 🌐 JavaScript | 📅 2019-05-31 - Obscure text with messed font
* [marked](https://github.com/amio/marked) ⭐ 21 | 🐛 2 | 🌐 JavaScript | 📅 2022-12-06 - Markdown render service
* [MicroFrontier](https://github.com/adileo/MicroFrontier) ⭐ 8 | 🐛 0 | 🌐 TypeScript | 📅 2021-11-04 - URL Crawler Frontier backed by Micro and Redis
* [micro-analytics-events](https://github.com/HugoDF/micro-analytics-events) ⚠️ Archived - A service to record analytics events to SQLite3
* [micro-figma](https://github.com/jongold/micro-figma) - Add authentication with Figma to your application
* [Caravaggio](https://gitlab.com/ramiel/caravaggio) - Image manipulation proxy

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-26._
