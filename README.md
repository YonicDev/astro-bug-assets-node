# Astro Bug Minimal Code Project

This is a project for an Astro bug where experimental assets does not work with Node.js SSR adapter.

## Reproduction

Clone this repository, and run:

```sh
$ npm install
$ npm run build
$ node ./dist/server/entry.mjs
```

Follow the same steps if you're going to use an sandboxed environment:

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/YonicDev/astro-bug-assets-node)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/YonicDev/astro-bug-assets-node)