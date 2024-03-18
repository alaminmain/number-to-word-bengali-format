
# Number to word in Bengali format

A JavaScript function to convert numbers to words in Bengali taka format.

This module contains a single function number2text that converts a number to its corresponding word representation. It supports numbers up to 999,999,999,999,999.99 and can be used to convert both integers and decimal numbers.

## Usage/Examples

```javascript
const number2text = require('numbertoword.js').number2text;

console.log(number2text(10000)); // Output: ten thousand Taka
```
The number2text function returns a string that represents the number in words. It also supports decimal numbers:

```javascript
console.log(number2text(123.45)); // Output: one hundred twenty three Taka and forty five Paise
```
Here's another Examples
```javascript
console.log(number2text(9999999999999)); 
// Output:  NINE LAC NINETY-NINE THOUSAND NINE HUNDRED AND NINETY-NINE CRORE NINETY-NINE LAC NINETY-NINE THOUSAND NINE HUNDRED AND NINETY-NINE TAKA ONLY
```
## Limitation
The number2text function supports numbers up to 999,999,999,999,999.99. It does not support negative numbers or numbers outside of this range.
## License

[MIT](https://choosealicense.com/licenses/mit/)


## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.

