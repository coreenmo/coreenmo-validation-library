
## 💾 Requirements

* `Web Browser` - Can be used as an emulator to build applications. Example [Chrome, Firefox, Safari & Opera].
* `Internet` - Because many use CDN and to make it easier to find solutions to all problems.

## 🎯 How To Use

#### Example Syntax

```javascript
const ValidationLibrary = require('./src/validation');

// Example usage of validateEmail function
const isValidEmail = ValidationLibrary.validateEmail('test@example.com');
console.log('Is valid email?', isValidEmail); // Output: true

// Example usage of validateURL function
const isValidURL = ValidationLibrary.validateURL('https://example.com');
console.log('Is valid URL?', isValidURL); // Output: true
```

#### Explanation

* `validateEmail(email)`: Validates the format of an email address.
* `validateURL(url)`: Validates the format of a URL.

#### Return Value

* Each validation function returns true if the input passes the validation, and false otherwise.
