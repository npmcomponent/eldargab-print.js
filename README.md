*This repository is a mirror of the [component](http://component.io) module [eldargab/print.js](http://github.com/eldargab/print.js). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/eldargab-print.js`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
#print.js

Mini template (format) function for html, urls, etc

##Examples

```javascript
var print = require('print')
print.html('Hello {}', '<world>!') //=> 'Hello &lt;world&gt;!'
print.html('Hello {!}', '<em>world!</em>') //=> 'Hello <em>world!</em>'
print.html('{2}, {1}, {0}', 0, 1, 2) //=> '3, 2, 1'
print.url('/{}', 'hello world') // => '/hello%20world'
```

##Installation

via component

```
component install eldargab/print.js
```

##License

MIT
