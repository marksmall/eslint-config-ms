# Node Project Config

- [Node Project Config](#node-project-config)
  - [Overview](#overview)
  - [Usage](#usage)

## Overview

The project is an NPM project to manage my preferred ESLint and Prettier configuation.
For more info, see the `README.md` files in each package.

## Usage

To use this library in your application's ESLint config file `eslint.config.js`, then do:

```javascript
  // eslint.config.js
  import myconfig from "eslint-config-ms";

  export default [
    ...myconfig,
  ]
```