
[![Build Status](https://secure.travis-ci.org/soldair/node-ua-device-type.png)](http://travis-ci.org/soldair/node-ua-device-type)

ua-device-type
==============

user agent based device type sniffer tablet||mobile||desktop||tv
based and almost wholely the matching code from the npm package express-device by rguerreiro

example
=======

```js

var deviceType = require('ua-device-type');

deviceType('Mozilla/5.0 (Linux; Android 4.1.1; Nexus 7 Build/JRO03S) AppleWebKit/535.19 (KHTML, like Gecko) Chrome/18.0.1025.166 Safari/535.19') === "tablet"

// true

```

api
===

deviceType(user agent string)

return values
-------------
String

- "tablet"
- "mobile"
- "default"


thanks
======

Special thanks to rguerreiro author of https://github.com/rguerreiro/express-device
who tracked down the device matching code from https://github.com/bjankord/Categorizr

I needed to use this without using express. its a small lib so i bundled it up for all to enjoy.

