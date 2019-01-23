# xcx_wxParse
小程序富文本

先在头部引入：

```js
const WxParse = require('../../utils/wxParse/wxParse.js');
```

再使用：

```js
WxParse.wxParse('detail', 'html', data.content, that, 25);
```