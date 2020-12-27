## Singapore IC Validator

A fast and easy to use Singapore IC validator.
## Install

```
npm i singapore-ic-validator
```

## Usage

```javascript
const validateNRIC = require('singapore-ic-validator');

let result = validateNRIC('SXXXXXXXJ');
```

If the returned value is `true`, then validation succeeds. 

If the returned value is `false`, then validation fails.