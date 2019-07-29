### gatehub
---
https://gatehub.net/

https://github.com/GateHubNet

```
// https://github.com/GateHubNet/FileSaver.js
// 
try {
  var isFileSaverSupported = !!new Blob;
} catch (e) {}

boolean saveTextAs(in textContent, in fileName, in charset)

FileSaver saveAs(in Blob data, in DOMString filename)

saveTextAs("Hi,This,is,a,CSV,File", "test.csv")
saveTextAs("<div>Hello, world!</div>", "test.html")

var blob = new Blob(["Hello, world!"], {type: "text/plain;charset=utf-8"});
saveAs(blob, "hello world.txt");

var canvas = document.getElementById("my-canvas"), ctx = canvas.getContext("2d");
canvas.toBlob(function(blob) {
  saveAs(blob, "pretty image.png");
});
```

```
```

```
```


