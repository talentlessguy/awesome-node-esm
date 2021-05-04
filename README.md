# Awesome Node ESM

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

A curated list of Node.js modules with native ESM support and resources about ES Modules in Node.js.

## Contents

- [Articles](#articles)
- [Tools](#tools)
- [Packages](#packages)
  - [Web frameworks](#web-frameworks)
  - [HTTP](#http)
  - [Body parsers](#body-parsers)
  - [Static servers](#static-servers)
  - [Template engines](#template-engines)
  - [SSR tools](#ssr-tools)
  - [Databases](#databases)
  - [Logging](#logging)
  - [Testing](#testing)
  - [CLI](#cli)
  - [Date](#date)
  - [File system](#file-system)
  - [Utility](#utility) (value manipulations)
  - [Random](#random)
  - [Parsing](#parsing)
  - [Compression](#compression)
  - [Performance](#performance)
  - [AST](#ast)
  - [Functional programming](#functional-programming)
  - [Math](#math)
  - [Other](#other)

## Articles

- [ECMAScript Modules Node.js docs](https://nodejs.org/api/esm.html)
- [Using ES modules natively in Node.js](https://2ality.com/2017/09/native-esm-node.html)
- [ES Modules in Node today](https://blog.logrocket.com/es-modules-in-node-today)

## Tools

- [esbuild](https://github.com/evanw/esbuild) - an extremely fast JavaScript bundler and minifier.
- [tsup](https://github.com/egoist/tsup) - bundle your TypeScript library with no config, powered by esbuild.
- [rollup](https://github.com/rollup/rollup) - next-generation ES Module bundler.
- [dual-publish](https://github.com/ai/dual-publish) - publish JS project as dual ES modules and CommonJS package to npm
- [cjstoesm](https://github.com/wessberg/cjstoesm) - tool that can transform CommonJS to ESM 

## Packages

### Web frameworks

- [tinyhttp](https://github.com/talentlessguy/tinyhttp) - tiny web framework as a replacement of Express.
- [polka](https://github.com/lukeed/polka) (alpha only) - micro web server so fast, it'll make you dance!
- [koa](https://github.com/koajs/koa) - expressive middleware for node.js using ES2017 async functions 

### HTTP

#### HTTP Clients

- [node-fetch](https://github.com/node-fetch/node-fetch) - light-weight module that brings window.fetch to Node.js
- [httpie](https://github.com/lukeed/httpie) - a Node.js HTTP client as easy as pie!

#### API Clients

- [kitsu](https://github.com/wopian/kitsu) - simple, lightweight & framework agnostic JSON:API client
- [twitter-lite](https://github.com/draftbit/twitter-lite) - tiny, full-featured, flexible client / server library for the Twitter API 

### Body parsers

- [milliparsec](https://github.com/talentlessguy/milliparsec) - tiniest Node.js body parser ever

### Static servers

- [sirv](https://github.com/lukeed/sirv) - an optimized middleware & CLI application for serving static files~! 

### Template engines

- [eta](https://github.com/eta-dev/eta) - embedded JS template engine for Node, Deno, and the browser

### SSR

- [preact-render-to-string](https://github.com/preactjs/preact-render-to-string) - universal rendering for Preact: render JSX and Preact components to HTML.
- [hyperapp-render](https://github.com/kriasoft/hyperapp-render) - render Hyperapp to an HTML string with SSR and Node.js streaming support.
- [hypermdx](https://github.com/talentlessguy/hypermdx) - Markdown enhanced with Hyperapp 
- [streamdown](https://github.com/talentlessguy/streamdown) - stream markdown to HTML 

### Databases

- [rxdb](https://github.com/pubkey/rxdb) - a realtime Database for JavaScript Applications.

### Logging

- [logtown](https://github.com/logtown/logtown) - simple Logging Facade for JavaScript.
- [oddlog](https://gitlab.com/frissdiegurke/oddlog) - high-performance payload focused logging library for node.js.
- [diary](https://github.com/maraisr/diary) - zero-dependency, fast logging library for both Node and Browser.
- [roarr](https://github.com/gajus/roarr) - JSON logger for Node.js and browser.

### Testing

- [uvu](https://github.com/lukeed/uvu) - an extremely fast and lightweight test runner for Node.js and the browser.
- [oletus](https://github.com/bearror/oletus) - minimal ECMAScript Module test runner

### CLI

#### Argument parsing

- [yargs](https://github.com/yargs/yargs) - Command-line parser that automatically generates an elegant user-interface.

#### Colors

- [colorette](https://github.com/jorgebucaran/colorette) - color your terminal using pure idiomatic JavaScript.
- [kleur](https://github.com/lukeed/kleur) - the fastest Node.js library for formatting terminal text with ANSI colors~!

### Date

- [dayjs](https://github.com/iamkun/dayjs) - 2KB immutable date library alternative to Moment.js with the same modern API
- [tinydate](https://github.com/lukeed/tinydate) - a tiny (349B) reusable date formatter. 
- [tempe](https://github.com/masbagal/tempe) - Featherlight (< 2kB) helper for Javascript date formatting
- [light-date](https://github.com/xxczaki/light-date) - blazing fast & lightweight (157 bytes) date formatting for Node.js and the browser. 

### File system

- [istextorbinary](https://github.com/bevry/istextorbinary) - Check if a file is text or binary.
- [@tinyhttp/dotenv](https://github.com/talentlessguy/tinyhttp/tree/master/packages/dotenv) - A rewrite of [dotenv](https://github.com/motdotla/dotenv) module.

### Utility

- [dequal](https://github.com/lukeed/dequal) - tiny (304B to 489B) utility to check for deep equality
- [klona](https://github.com/lukeed/klona) - tiny (240B to 507B) and fast utility to "deep clone" Objects, Arrays, Dates, RegExps, and more!
- [dlv](https://github.com/developit/dlv) - Safe deep property access in 120 bytes. x = dlv(obj, 'a.b.x')


### Random

- [uuid](https://github.com/lukeed/uuid) - tiny (230B), fast, and cryptographically secure UUID (V4) generator for Node and the browser
- [nanoid](https://github.com/ai/nanoid) - Tiny, secure, URL-friendly, unique string ID generator.

### Parsing

- [snarkdown](https://github.com/developit/snarkdown) - a snarky 1kb Markdown parser written in JavaScript

### Compression

- [anzip](https://github.com/mikbry/anzip) - simple async unzip library for Node.js

### Performance

- [piscina](https://github.com/piscinajs/piscina) - a fast, efficient Node.js Worker Thread Pool implementation
- [nanodelay](https://github.com/ai/nanodelay) - a tiny (25 bytes) Promise wrapper around setTimeout 

### AST

- [acorn](https://github.com/acornjs/acorn) - a small, fast, JavaScript-based JavaScript parser

### Functional programming

- [immutable](https://github.com/facebook/immutable-js) - Immutable data collections.
- [ramda](https://github.com/Ramda/ramda) - practical functional Javascript.
- [smoldash](https://github.com/marvinhagemeister/smoldash) - A tiny lodash alternative built for the modern web
- [deepdash](https://github.com/YuriGor/deepdash) - tree traversal library written in Underscore/Lodash fashion 

### Math

- [mathjs](https://github.com/josdejong/mathjs) - An extensive math library.

### Other

- [turf](https://github.com/Turfjs/turf) - a modular geospatial engine written in JavaScript 
- [cashify](https://github.com/xxczaki/cashify) - lightweight currency conversion library, successor of money.js
- [microsite](https://github.com/natemoo-re/microsite/) - fast, opinionated static site generator powered by Snowpack
- [transliterate](https://github.com/sindresorhus/transliterate) - convert Unicode characters to Latin characters using transliteration 
