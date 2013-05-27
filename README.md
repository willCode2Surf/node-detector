
# detector

detector 是根据 UserAgent 信息识别客户端的模块，可以用于在服务端处理 UserAgent
识别客户端。

另外有一个更适合在客户端浏览器运行的版本的 [detector](https://github.com/aralejs/detector)

## 使用说明

```js
var detector = require("detector");
var ua = "Mozilla/5.0 (Macintosh; Intel Mac OS X 10_8_3) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/27.0.1453.93 Safari/537.36";
console.log(detector.detect(ua));
```

## API

### {Object} detector.detect(String userAgent)

根据指定 userAgent 识别客户端信息。

这个 API 延续了基于浏览器运行的版本，但似乎基于 node 的版本无需这么累赘，
请[参与讨论](https://github.com/hotoo/node-detector/issues/1) 。
