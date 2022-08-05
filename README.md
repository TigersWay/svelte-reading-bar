# reading-bar  ![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/tigersway/svelte-reading-bar?style=flat-square) ![GitHub last commit](https://img.shields.io/github/last-commit/tigersway/svelte-reading-bar?style=flat-square) ![GitHub issues](https://img.shields.io/github/issues/tigersway/svelte-reading-bar?style=flat-square)

## Usage

### via CDN  [![jsDelivr hits (npm)](https://img.shields.io/jsdelivr/npm/hm/@tigersway/reading-bar?label=jsDelivr&logo=jsdelivr&style=flat-square)](https://www.jsdelivr.com/package/npm/@tigersway/reading-bar)

```html
<!doctype html>
<html class="no-js" lang="en">
<head>
...
<body>
  <reading-bar selector="article" height=".4em" background="linear-gradient(to right, green, lime)"></reading-bar>
...
  <script src="https://cdn.jsdelivr.net/npm/@tigersway/reading-bar@1.0.0"></script>
</body>
</html>
```

### via npm/pnpm/yarn  [![npm](https://img.shields.io/npm/dm/@tigersway/reading-bar?label=npmjs&logo=npm&style=flat-square)](https://www.npmjs.com/package/@tigersway/reading-bar)

... and your bundler!

```js
import '@tigersway/reading-bar';
```

### Options

- `selector`: (default body) CSS selector for the readable part of that page,
- `height`: (default 4px) CSS height of the bar,
- `background`: (default linear-gradient(to right, #4169e1, #c6d2f6)) CSS background as color, gradient, etc

## CHANGELOG

- **v1.0.0**
  - First public release
