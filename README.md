# PROPOSAL: newtonjs/body #

Rigid body.

**Version:** *0.0.1*<br/>
**Build status:** [![Build Status][travis-status]][travis]


### Proposed usage ###

```js
var body = require('newtonjs-body');

var marble = new body.RigidBody(new body.Vector([x, y]), [mass]);
var table  = new body.Plane(new body.Vector([x, y]));
// to be continued...

// ...when I have time
```


### Contributing ###

We accept contributions to the proposal via Pull Request or by submitting an Issue.


### License ###
The content of this library is released under the **MIT License** by **Andrew Lawson**.<br/>
You can find a copy of this license at http://www.opensource.org/licenses/mit


<!-- Links -->
[travis]: https://travis-ci.org/newtonjs/body
[travis-status]: https://travis-ci.org/newtonjs/body.png
