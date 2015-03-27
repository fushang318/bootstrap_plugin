# popover
Bootstrap 弹出框（Popover）插件

弹出框（Popover）与工具提示（Tooltip）类似，提供了一个扩展的视图。如需激活弹出框，用户只需把鼠标悬停在元素上即可(可以改变触发条件为点击，悬停，手动等等)。弹出框的内容完全可使用 Bootstrap 数据 API（Bootstrap Data API）来填充。该方法依赖于工具提示（tooltip）。

## 网址 
http://getbootstrap.com/javascript/#popovers

## 前段代码

HTML
```html
  <a href="#" id="example" class="btn btn-success" data-content="我是内容" title="我是标题">点我</a>
```

JS
```js
  $('#example').popover(各种参数);
```


## 页面效果

平时的状态

![](http://img.teamkn.com/i/EsmPYyPs.png)

鼠标点击后的状态

![](http://img.teamkn.com/i/rFyoNNSP.png)