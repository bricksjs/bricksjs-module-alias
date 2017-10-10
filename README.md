# Module require alias
> Create CommonJS alias without any dependency

## Usage

### .gitignore
Only ignore main node_modules
```
/node_modules
```

### Create your module index.js
```js
// Call the alias
var dummy = require('dummy');
module.exports = {}
```

### Create your alias in node_modules folder at same level or higher
