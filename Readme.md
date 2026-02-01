
# axon_msgpack

  Axon msgpack codec

## Installation

```
$ npm install axon-msgpack
```

## Usage

```js
var axon = require('axon');
require('axon-msgpack');

var sock = axon.socket('pub');
sock.format('msgpack');
sock.send({ hello: new Buffer('world') });
```




































