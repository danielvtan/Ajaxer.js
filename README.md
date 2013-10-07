# Ajaxer.js
A simple ajax class

## Using GET

```javascript
// get(url,callBack);
Ajaxer.get("http://danielvtan.com/ajax.php?query=here", function(e) {
   var json = eval('(' + e + ')');
});
```

## Using GET
```javascript
// post(url,dataObject,callBack);
Ajaxer.post("http://danielvtan.com/ajax.php", { test:"1", ola:"2" }, function(e) {
   var json = eval('(' + e + ')');
});
```