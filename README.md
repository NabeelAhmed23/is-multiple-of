# is-divisible-by

A simple utility function to check if a target number is divisible by a denominator.

## Installation

```bash
npm install is-divisible-by
```

## Usage

```javascript
const isDivisibleBy = require('is-divisible-by');

// Basic usage
console.log(isDivisibleBy(10, 5)); // true
console.log(isDivisibleBy(10, 3)); // false
console.log(isDivisibleBy(0, 5));  // true
console.log(isDivisibleBy(15, 3)); // true
```

## API

### isDivisibleBy(target, denom)

Returns `true` if `target` is a multiple of `denom`, `false` otherwise.

#### Parameters

- `target` (number): The number to check
- `denom` (number): The denominator to check against

#### Returns

- (boolean): `true` if target is a multiple of denom, `false` otherwise

## Examples

```javascript
const isDivisibleBy = require('is-divisible-by');

// Check if 12 is a multiple of 4
isDivisibleBy(12, 4); // true

// Check if 13 is a multiple of 4
isDivisibleBy(13, 4); // false

// Check if 0 is a multiple of any number
isDivisibleBy(0, 7); // true

// Negative numbers work too
isDivisibleBy(-8, 4); // true
isDivisibleBy(-7, 4); // false
```

## License

MIT

## Author

Nabeel Ahmed