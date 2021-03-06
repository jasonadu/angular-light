### Angular Light
Web framework with MVC model. Angular.js + Knockout.js way.

Visit [angularlight.org](http://angularlight.org/), [Docs](http://angular-light.readthedocs.io/en/latest/docs0.html)

[![Join the chat at https://gitter.im/lega911/angular-light](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/lega911/angular-light?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

### Download / Install
* ```bower install alight```
* ```npm install alight```
* [Download any version here](https://github.com/lega911/alight/releases)

### Example 0
``` html
<div al-app>
    <label>Name:</label>
    <input type="text" al-value="name" />
    <h3>Hello {{name}}!</h3>
</div>
```

### Example 1
``` html
<div id="app">
    <input al-value="name" type="text" />
    {{name}} <br/>
    <button al-on.click="click()">Set Hello</button>
</div>
```

``` js
alight('#app', {
    name: 'Some text',
    click: function() {
        this.name = 'Hello'
    }
});
```

[More examples](http://angularlight.org/doc/examples.html)

### Browser Support
Google Chrome, Firefox, IE9+ (IE8 with jQuery)

### Building and testing
```
npm install
gulp
gulp test
```

Sources of 0.7.15 and older ones there: https://bitbucket.org/lega911

### License
[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2013 - 2016 Oleg Nechaev <lega911@gmail.com>
