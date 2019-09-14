# jrot

is characters rotation and you can customaise it 

# exaampel

```js
const Jrot = require('jrot');

var rot13 = new Jrot({
    data : new Jrot.JData([1.9], ["a","z"])
    rc : 13
})

var str = "some text";
<<<<<<< HEAD
=======

>>>>>>> v-2.0.0
var estr = rot13.encode(str);
var dstr = rot13.decode(estr);

console.log(str === dstr); // true

```
