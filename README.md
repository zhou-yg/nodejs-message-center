# message-proxy

## run server


> npm install message-proxy

> npx run mp [port] [name]

## visit

> localhost:[port]/a/b/c

## client

> npm install message-proxy


```javascript
let s = require('../lib/client');

s.config([port], [remote host], [my-client-name]);

s.on('cmd', (cmd, a) => {
  console.log(cmd, a); // output -> a, /b/c
});

```
