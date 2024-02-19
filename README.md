# prettier-config

This package contains the core prettier config.

## Setup

- add this package by running `npm i @tkakhter/prettier-config --save-dev`
- Use `.prettierrc.js` which only needs to contain the following line:

```javascript
module.exports = require("@tkakhter/prettier-config");
```

In case you need to override some settings this can be done like this:

```javascript
module.exports = {
  ...require("@tkakhter/prettier-config"),
  useTabs: true,
};
```

## Versioning

Eslint integrates with prettier so we're matching major version numbers with eslint

## Documentation

Options: https://prettier.io/docs/en/options.html
Blog: https://prettier.io/blog/
