##koa-redirect-mobile

check request from mobile or pc, and redirect to mobile or pc;


##Install

```
npm install koa-redirect-mobile
```



##Example


```
var koa = require('koa');
var recirect = require('koa-redirect-mobile');

var app = kao();

var mobileUrl = "http://m.baidu.com";
app.use(redirect(mobileUrl));
// or use app.use(redirect());   ##默认  redirect(m.url);



app.listen(3000);

```


##TODO
