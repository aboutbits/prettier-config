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

## Build & Publish

To build and publish the package, visit the GitHub Actions page of the repository.

You can choose between two workflows:
- `Release Package` to publish a new version of the package.
- `Pre-Release Package` to publish a new pre-release version of the package.

**Note:** Pre-releases need to be supplied with a pre-id.

**Note:** To increment a pre-release, you have to run the normal release workflow and select "prerelease". For this action you need to already be on a pre-release version.

## Information

AboutBits is a company based in South Tyrol, Italy. You can find more information about us on [our website](https://aboutbits.it).

### Support

For support, please contact [info@aboutbits.it](mailto:info@aboutbits.it).

### Credits

- [All Contributors](../../contributors)

### License

The MIT License (MIT). Please see the [license file](license.md) for more information.
