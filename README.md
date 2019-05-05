[![Build Status](https://travis-ci.org/kaelzhang/request-fallback.svg?branch=master)](https://travis-ci.org/kaelzhang/request-fallback)
[![Coverage](https://codecov.io/gh/kaelzhang/request-fallback/branch/master/graph/badge.svg)](https://codecov.io/gh/kaelzhang/request-fallback)
<!-- optional appveyor tst
[![Windows Build Status](https://ci.appveyor.com/api/projects/status/github/kaelzhang/request-fallback?branch=master&svg=true)](https://ci.appveyor.com/project/kaelzhang/request-fallback)
-->
<!-- optional npm version
[![NPM version](https://badge.fury.io/js/request-fallback.svg)](http://badge.fury.io/js/request-fallback)
-->
<!-- optional npm downloads
[![npm module downloads per month](http://img.shields.io/npm/dm/request-fallback.svg)](https://www.npmjs.org/package/request-fallback)
-->
<!-- optional dependency status
[![Dependency Status](https://david-dm.org/kaelzhang/request-fallback.svg)](https://david-dm.org/kaelzhang/request-fallback)
-->

# request-fallback

request which fallbacks to other cache mechanism if any error occurs

## Install

```sh
$ npm i request-fallback
```

## Usage

```js
const request = require('request-fallback')

request({
  url,
  fallback (req, res) {

  }
}).pipe(res)
```

## License

[MIT](LICENSE)
