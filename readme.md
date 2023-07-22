# @aboutbits/prettier-config

[![npm package](https://badge.fury.io/js/%40aboutbits%2Fprettier-config.svg)](https://badge.fury.io/js/%40aboutbits%2Fprettier-config)
[![license](https://img.shields.io/github/license/aboutbits/prettier-config)](https://github.com/aboutbits/prettier-config/blob/main/license.md)

AboutBit's [prettier](https://prettier.io/) config

## Usage

Install the package:

```sh
npm i -D @aboutbits/prettier-config
```

Edit `package.json`:

```json
{
  // ...
  "prettier": "@aboutbits/prettier-config"
}
```

### Extend the preset

Create a `.prettierrc.js` file:

```js
const aboutBitsConfig = require('@aboutbits/prettier-config')

module.exports = {
  ...aboutBitsConfig,
  singleQuote: false,
}
```

## Publish

To publish the package commit all changes and push them to main. Then run one of the following commands locally:

```sh
npm version patch
npm version minor
npm version major
```

## Information

AboutBits is a company based in South Tyrol, Italy. You can find more information about us on [our website](https://aboutbits.it).

### Support

For support, please contact [info@aboutbits.it](mailto:info@aboutbits.it).

### Credits

- [All Contributors](../../contributors)

### License

The MIT License (MIT). Please see the [license file](license.md) for more information.
