# basic-color-types <br> [![NPM Version](https://img.shields.io/npm/v/@chriscodesthings/basic-color-types)](https://www.npmjs.com/package/@chriscodesthings/basic-color-types) [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

> **Defines named types for common color formats**

## Description

Provides named types for common color formats.

### See...
- [Install](#install "Install")
- [Types](#types "Types")
- [See Also](#see-also "See Also")

---

## Install

```sh
npm install --save @chriscodesthings/basic-color-types
```

## Types

These types are made available:

```ts
export type cssHexCode = string;
export type rgbColor = [number, number, number];
export type rgbaColor = [number, number, number, number];
```

### TypeScript

To use the types in your TypeScript project:

```js
import type { rgbColor } from '@chriscodesthings/basic-color-types';

const myColor: rgbColor = [100, 149, 237];
```

### JavaScript

You can also use types in JavaScript with JSDoc with `@typedef` imports:

```js
/**
 * @typedef {import('@chriscodesthings/basic-color-types').rgbaColor} rgbaColor
 */

/** @type {rgbaColor} */
const myColor = [100, 149, 237, 1];
```

## See Also...

- [**color-object**: Simple, lightweight class to store and manipulate a color, and convert between formats](https://github.com/ChrisCodesThings/color-object "Simple, lightweight class to store and manipulate a color, and convert between formats")
- [**is-css-hex-color**: Determine if a string is a CSS hex color code](https://github.com/ChrisCodesThings/is-css-hex-color "Determine if a string is a CSS hex color code")
- [**color-looks-like-rgba**: Determine if a set of values could be an RGB or RGBA color](https://github.com/ChrisCodesThings/color-looks-like-rgba "Determine if a set of values could be an RGB or RGBA color")
