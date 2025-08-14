eight-dot-matrix
========================================
A npm package that provides Unicode characters for 8 dot matrix.

Install
----------------------------------------


Usage
----------------------------------------
### Basic

```js
import { EIGHT_DOT_MATRIX } from 'eight-dot-matrix';

console.log(EIGHT_DOT_MATRIX[0][0][0][0][0][0][0][0]); // "⠀" This is a space that is not a normal space.
console.log(EIGHT_DOT_MATRIX[1][1][1][1][1][1][1][1]); // "⣿"
console.log(EIGHT_DOT_MATRIX[1][0][0][1][0][0][1][0]); // "⢕"
```

### Dot pattern description
8 dot matrix is as follows:

```
| 0 1 |
| 2 3 |
| 4 5 |
| 6 7 |
```

Each dot position is represented by 0 (off) or 1 (on).

Example:
- `"00000000"` → all dots are off
- `"11111111"` → all dots are on
- `"10101010"` → left side dots are on


License
----------------------------------------
MIT

Contributing
----------------------------------------
Pull requests and issue reports are welcome. 

