# deslice

Double-ended slice method (Array.prototype.slice).

[![npm](https://img.shields.io/npm/v/deslice)](https://www.npmjs.com/package/deslice)
[![Build Status](https://travis-ci.com/alexengrig/deslice.svg?branch=master)](https://travis-ci.com/alexengrig/deslice)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)

## Installation

```bash
npm add deslice
```

## Usage

```javascript
import deslice from 'deslice';

const arr = [0, 1, 2, 3, 4, 5]

deslice(arr)         // > [0, 1, 2, 3, 4, 5]
deslice(arr, 3)      // > [3, 4, 5]
deslice(arr, -3)     // > [3, 4, 5, 0, 1, 2]
deslice(arr, 2, 4)   // > [2, 3]
deslice(arr, 2, -2)  // > [2, 3]
deslice(arr, -2, 2)  // > [4, 5, 0, 1]
```

## License

This project is [licensed](LICENSE) under [Apache License, version 2.0](https://www.apache.org/licenses/LICENSE-2.0).
