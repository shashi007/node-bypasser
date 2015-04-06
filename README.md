# node-bypasser
Bypass URL shortener websites

## Example:

```javascript
var Bypasser = require('./node-bypasser/bypasser.js');

var w = new Bypasser('http://adf.ly/1DX0XD');
w.decrypt(function(err, result) {
	console.log('Decrypted: ' + result);
});
```

The output will be 
```
Decrypted: https://github.com/matteocontrini/node-bypasser/
```

## Supported websites
* Adf.ly

## Coming soon
```
// TODO linkbucks.com
// TODO sh.st
// TODO adfoc.us
// TODO bit.ly
// TODO goo.gl
```