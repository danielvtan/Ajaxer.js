#Ajaxer.js
A simple ajax class

##Using GET

```javascript
// async callback
function onComplete(e) {
   var json = eval('(' + e + ')');
}
// get(url,callBack);
Ajaxer.get("http://danielvtan.com/ajax.php?query=here", onComplete);
```
##Using GET
```javascript
// post(url,dataObject,callBack);
Ajaxer.post("http://danielvtan.com/ajax.php", { test:"1", ola:"2" }, onComplete);
```