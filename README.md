# node-zip
zip and unzip folder for node

# ��װ

```
npm install node-zip-dir
```

# ʹ��

```
var zip = require('node-zip-dir');

// ѹ��
zip.zip('E:/Temp', 'E:/Temp.zip').then(function() {
    console.log('success');
}).catch(function(err) {
    console.error(err);    
});

// ��ѹ
zip.unzip('E:/Temp.zip', 'E:/Temp1').then(function() {
    console.log('success');
}).catch(function(err) {
    console.error(err);    
});

```



