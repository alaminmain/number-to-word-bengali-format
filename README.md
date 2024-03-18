Numbertoword.js
A JavaScript function to convert numbers to words

Description
This module contains a single function number2text that converts a number to its corresponding word representation. It supports numbers up to 999,999,999,999,999.99 and can be used to convert both integers and decimal numbers.

Installation
To install the module, run the following command:

bash
Copy code
npm install numbertoword.js
Usage
To use the number2text function, import it into your JavaScript file and call it with a number as an argument:

javascript
Copy code
const number2text = require('numbertoword.js').number2text;

console.log(number2text(10000)); // Output: ten thousand Taka
The number2text function returns a string that represents the number in words. It also supports decimal numbers:

javascript
Copy code
console.log(number2text(123.45)); // Output: one hundred twenty three Taka and forty five Paise
Limitations
The number2text function supports numbers up to 999,999,999,999,999.99. It does not support negative numbers or numbers outside of this range.

API
number2text(value: number): string
Converts a number to its corresponding word representation.

Parameters
value (number): The number to convert to words.
Returns
string: The word representation of the number.

License
MIT

Contributing
Contributions are welcome! Please submit a pull request with your changes.

Support
If you encounter any problems or have any questions, please open an issue on the GitHub repository.

Acknowledgements
This module was inspired by the following resources:

Convert numbers to words in JavaScript
How to convert numbers to words in JavaScript
Note
This module is for educational purposes only and should not be used for any production applications.
