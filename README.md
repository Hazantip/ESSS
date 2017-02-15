# es6-webpack2-starter

> A template project for ECMAScript(latest), webpack2, sass and postcss.

## Features

* es6: by babel and it's presets and plugins
* css module: by css-loader
* sass: by sass-loader
* webpack2 provides faster compilation
* auto-reload by webpack-dev-server

## Installation

    $ npm install
    # or
    $ yarn install

## Configuration

1. Copy then rename `env.example.js` to `env.js` if it is not done automatically by `postinstall`.

You can custom your local environment via `env.js`, so that it does not affect others.

## Run in development

    $ npm start

## Build for production

    $ npm run build

This will generator minified css and scripts to `dist/`.

## Proxy

You can change your proxy rules in `proxy/rules`.

## Based on

[https://github.com/micooz/es6-webpack2-starter](https://github.com/micooz/es6-webpack2-starter/).

