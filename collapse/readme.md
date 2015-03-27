# Collapse

Bootstrap 折叠（Collapse）插件

## 网址
http://getbootstrap.com/javascript/#collapse

## 前段代码

HTML
```html
   <div>
      <a data-toggle="collapse" href="#item1" >点我折叠或者展开 item1 content</a>
      <div id="item1">
        item1 content
      </div>
    </div>
    <div>
      <a data-toggle="collapse" href="#item2" >点我折叠或者展开 item2 content</a>
      <div id="item2">
        item2 content
      </div>
    </div>
```

另外也可以用 js 代码来控制某一块是否折叠
```js
// 展开 .item1 内容
$('.item1').collapse("show")

// 折叠 .item1 内容
$('.item1').collapse("hide")
```

## 页面效果

折叠状态

![](http://img.teamkn.com/i/UdlejcvC.png)

展开状态

![](http://img.teamkn.com/i/aDWRlT7w.png)