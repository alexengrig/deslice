# endless-slice

The slice method (Array.prototype.slice) but endless.

[![npm](https://img.shields.io/npm/v/endless-slice)](https://www.npmjs.com/package/endless-slice)
[![Build Status](https://travis-ci.com/alexengrig/endless-slice.svg?branch=master)](https://travis-ci.com/alexengrig/endless-slice)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)

## Instalation

```bash
npm add endless-slice
```

## Usage

```javascript
import slice from 'endless-slice';

const arr = [0, 1, 2, 3, 4, 5];

slice(arr); // => [0, 1, 2, 3, 4, 5]

slice(arr, 3); // => [3, 4, 5]

slice(arr, -2); // => [4, 5]

slice(arr, 2, 4); // => [2, 3]

slice(arr, -2, 2); // => [4, 5, 0, 1]
```

## License

This project is [licensed](LICENSE) under [Apache License, version 2.0](https://www.apache.org/licenses/LICENSE-2.0).
