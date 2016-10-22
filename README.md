# react-instagram-embed

[![Build Status][travis-image]][travis-url]
[![Dependency Status][david-image]][david-url]
[![Devdependency Status][david-dev-image]][david-dev-url]
[![npm version][npm-image]][npm-url]
[![License][license-image]][license-url]

React embedding Instagram posts component

```sh
npm i react-instagram-embed
```

[Live demo](https://sugarshin.github.io/react-instagram-embed/)

## Usage

```js
import InstagramEmbed from 'react-instagram-embed';

<InstagramEmbed
  url='https://instagr.am/p/Zw9o4/'
  maxWidth={320}
  hideCaption
  onLoading={() => {}}
  onSuccess={() => {}}
  onFailure={() => {}}
/>
```

## props

- `url` {String} Instagram URL. Required
- `maxWidth` {Number} Max width. Minimum size is `320`. Default `undefined`
- `hideCaption` {Boolean} Default `false`
- `onLoading` {Function}
- `onSuccess` {Function}
- `onFailure` {Function}

## Contributing

1. Fork it!
2. Create your feature branch: git checkout -b my-new-feature
3. Commit your changes: git commit -am 'Add some feature'
4. Push to the branch: git push origin my-new-feature
5. Submit a pull request :D

## License

[MIT][license-url]

© sugarshin

[npm-image]: https://img.shields.io/npm/v/react-instagram-embed.svg?style=flat-square
[npm-url]: https://www.npmjs.org/package/react-instagram-embed
[travis-image]: https://img.shields.io/travis/sugarshin/react-instagram-embed/master.svg?branch=master&style=flat-square
[travis-url]: https://travis-ci.org/sugarshin/react-instagram-embed
[david-image]: https://david-dm.org/sugarshin/react-instagram-embed.svg?style=flat-square
[david-url]: https://david-dm.org/sugarshin/react-instagram-embed
[david-dev-image]: https://david-dm.org/sugarshin/react-instagram-embed/dev-status.svg?style=flat-square
[david-dev-url]: https://david-dm.org/sugarshin/react-instagram-embed#info=devDependencies
[license-image]: https://img.shields.io/:license-mit-blue.svg?style=flat-square
[license-url]: https://sugarshin.mit-license.org/
