# vuepress-theme-thindark

[![npm](https://img.shields.io/npm/v/vuepress-theme-thindark.svg)](https://www.npmjs.com/package/vuepress-theme-thindark)
[![npm](https://img.shields.io/npm/l/vuepress-theme-thindark.svg)](https://github.com/sqrthree/vuepress-theme-thindark/blob/master/LICENSE)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)

> A dark theme for VuePress. (It is remodeled from the [default theme](https://v1.vuepress.vuejs.org/theme/default-theme-config.html) and is compatible with all configurations of the default theme.)

[Live demo](https://lisniuse.github.io/vuepress-theme-thindark-demo/)

## Built With

- [Node.js](https://nodejs.org/)
- [VuePress](https://github.com/vuejs/vuepress)

## Prerequisites

There are some global dependencies you need to set up.

- [Node.js](https://nodejs.org/)
- [VuePress](https://github.com/vuejs/vuepress)

## Getting Started

### Installing

```bash
# Install vuepress
yarn global add vuepress # OR npm install -g vuepress

# Install theme
yarn global add vuepress-theme-thindark # OR npm install -g vuepress-theme-thindark
```

### Configuration

Create VuePress config file `.vuepress/config.js` and provide a `theme` option.

```js
// .vuepress/config.js
module.exports = {
  title: 'Hello, World.',
  description: 'dark theme for VuePress.',
  theme: 'api',
}
```

### As Easy as 1, 2, 3

```bash
# Create a markdown file and write something
echo '# Hello, World.' > Hello.md

# Start writing
vuepress dev .

# Build to static files
vuepress build .
```

## How to use?

Go to [docs](https://lisniuse.github.io/vuepress-theme-thindark-demo/) to get more details.
