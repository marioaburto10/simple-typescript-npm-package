# demo-pluralize-2
A demo Node.js module that returns the plural form of any noun. 
Note: This npm package was just created for the purpose of learning how to create an npm package. 

The module can be found on the [npm website](https://www.npmjs.com/package/demo-pluralize-2)

## Installation 
```sh
npm install demo-pluralize-2 --save
yarn add demo-pluralize-2
```
## Usage
### Javascript
```javascript
var pluralise = require('demo-pluralize-2');
var boys = pluralise.getPlural('Boy');
```
```sh
Output should be 'Boys'
```
### TypeScript
```typescript
import { getPlural } from 'demo-pluralize-2';
console.log(getPlural('Goose'))
```
```sh
Output should be 'Geese'
```
### AMD
```javascript
define(function(require,exports,module){
  var pluralise = require('demo-pluralize-2');
});
```