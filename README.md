# is-multiple-of

A simple utility function to check if a target number is a multiple of a denominator.

## Installation

```bash
npm install is-multiple-of
```

## Usage

```javascript
const isMultipleOf = require('is-multiple-of');

// Basic usage
console.log(isMultipleOf(10, 5)); // true
console.log(isMultipleOf(10, 3)); // false
console.log(isMultipleOf(0, 5));  // true
console.log(isMultipleOf(15, 3)); // true
```

## API

### isMultipleOf(target, denom)

Returns `true` if `target` is a multiple of `denom`, `false` otherwise.

#### Parameters

- `target` (number): The number to check
- `denom` (number): The denominator to check against

#### Returns

- (boolean): `true` if target is a multiple of denom, `false` otherwise

## Examples

```javascript
const isMultipleOf = require('is-multiple-of');

// Check if 12 is a multiple of 4
isMultipleOf(12, 4); // true

// Check if 13 is a multiple of 4
isMultipleOf(13, 4); // false

// Check if 0 is a multiple of any number
isMultipleOf(0, 7); // true

// Negative numbers work too
isMultipleOf(-8, 4); // true
isMultipleOf(-7, 4); // false
```

## License

ISC

## Author

Nabeel Ahmed