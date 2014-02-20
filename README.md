*This repository is a mirror of the [component](http://component.io) module [stagas/fan](http://github.com/stagas/fan). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/stagas-fan`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# fan

extracts argument names from a function descriptor

## example

```js
var fan = require('fan');

function greetings(hello, world){};

var args = fan(greetings);

console.log(args); // ["hello","world"]
```

## License

MIT
