# uuid-adv

Simple Module for generating uuid's

![random-string](https://api.travis-ci.org/valiton/node-random-string.png "random-string")

## Getting Started
Install the module with: `npm i uuid-adv`

```javascript
var uuid = require('uuid-adv');
var uuid_res = uuid(); // uuid_res contains now a uuid
```

## Documentation

You just need to install the package and then follow these steps

```javascript
var uuid = require('uuid-adv');
console.log(uuid());
```

```javascript
var uuid = require('uuid-adv');
const uuid_res = uuid();
console.log(uuid_res);
```

## Examples

```javascript
// that would be a call with all options (hint: thats a call with all defaults, und the options wouldnt be necessary in that case!)
var uuid = require('uuid-adv');
console.log(uuid());

Output: de05cf44-4596-468c-8160-6d7684eb6958

```

## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code using [Grunt](http://gruntjs.com/).


## Release History

- 1.0.0 Initial Release


## Contributors

- Irtaza Hussain


## License
Licensed under the MIT license.
