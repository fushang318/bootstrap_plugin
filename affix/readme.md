# affix
Bootstrap 自带的附加导航（Affix）插件，模仿CSS3 position:sticky 行为

## 网址 
http://getbootstrap.com/javascript/#affix

## 前段代码

### 纯 css 模式

HTML
```html
<div data-spy="affix" data-offset-top="60" data-offset-bottom="200">
  <!-- 导航内容-->
</div>
```

### JS 模式

HTML
```html
<div id="nav">
  <!-- 导航内容-->
</div>
```

JS
```js
$('#nav').affix({
  offset: {
    top: 100,
    bottom: function () {
      // 页面加载完后，获取页面底部元素的实际高度
      return (this.bottom = $('.footer').outerHeight(true))
    }
  }
})
```


## 页面效果

页面顶部
![](http://img.teamkn.com/i/KxwMSkBQ.png)

页面中部
![](http://img.teamkn.com/i/BFtipC02.png)