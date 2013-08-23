# Sandbox_GruntTDD

Verifying how mature are the TDD frameworks to develop through TDD.

*Everything running on Windows

## Getting Started
Install the module with: `npm install Sandbox_GruntTDD`

```javascript
var Sandbox_GruntTDD = require('Sandbox_GruntTDD');
Sandbox_GruntTDD.awesome(); // "awesome"
```

## Documentation
To install node.js and grunt templates I based on this blog: http://markdalgleish.com/2012/09/test-driven-node-js-development-with-grunt/

At the first beggining a faced a problem trying to use the templates.

With windows forget about this going smoothly.
```Batchfile
git clone git@github.com:gruntjs/grunt-init-node.git ~/.grunt-init/node
```
In my case the problem was that when I installed 'grunt-init', it went to "C:\\.grunt-init" instead of "%USERPROFILE%\\.grunt-init\\" as written in the documentation.

## Examples
After world cup

## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code using [Grunt](http://gruntjs.com/).

## Release History
_(Nothing yet)_

## License
Copyright (c) 2013 Luis Custodio  
Licensed under the MIT license.
