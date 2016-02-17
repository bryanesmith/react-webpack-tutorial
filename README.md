# react-webpack-tutorial

A mashup of the [React tutorial](https://facebook.github.io/react/docs/tutorial.html) and [webpack tutorial](https://webpack.github.io/docs/tutorials/getting-started/).

## Instructions

One-time setup:

```sh
npm install --global babel-cli
npm install --save react react-dom babel-preset-react
```

Compile jsx (continuous):

```sh
babel --presets react src --watch --out-dir public
```

Webpack bundling:

```sh
webpack public/scripts/main.js public/scripts/bundle.js
```

Run the server:

```sh
cd react
npm install
node server.js
```

Files will be served from `react-webpack-tutorial/public` (or from `server.js` perspective, `../public`).

## Development

JSX files modified in `src/`

HTML and CSS modified in `public/`. (This is weird...)
