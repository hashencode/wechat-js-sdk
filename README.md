微信官方 js-sdk
----

说明:

原项目（https://github.com/yanxi123-com/weixin-js-sdk）没有继续更新，故单开一个新的自用仓库。

仅将官方 js-sdk 发布到 npm，支持 CommonJS，便于 browserify, webpack 等直接使用，支持 TypeScript。


官方 JS 源码: https://res.wx.qq.com/open/js/jweixin-1.6.0.js

官方使用说明: https://developers.weixin.qq.com/doc/offiaccount/OA_Web_Apps/JS-SDK.html

安装:
```shell
npm install wechat-js-sdk
```

使用:
```javascript
// commonjs
var wx = require('wechat-js-sdk');

// es module
import wx from 'wechat-js-sdk'
```

### 感谢

TypeScript 定义文件来自 [wx-jssdk-ts](https://github.com/zhaoky/wx-jssdk-ts/blob/master/index.d.ts)
