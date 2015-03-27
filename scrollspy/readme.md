# scrollspy
Bootstrap 滚动监听（Scrollspy）插件，会根据滚动条的位置自动更新对应的导航目标。其基本的实现是随着您的滚动，基于滚动条的位置向导航栏添加 .active class。

## 网址 
http://getbootstrap.com/javascript/#scrollspy

## 前段代码

### 纯 css 模式

HTML
```html
<body data-spy="scroll" data-target=".navbar-content">
  <div class="navbar-example">
    <ul class="nav">
      <li><a href="#a">a</a></li>
      <li><a href="#b">b</a></li>
      <li><a href="#c">c</a></li>
    </ul>
  </div>
  <div class="navbar-content">
    <p id="a">blanblanblanblan</p>
    <p id="b">blanblanblanblan</p>
    <p id="c">blanblanblanblanblan</p>
  </div>
</body>
```

### JS 模式

HTML
```html
<body>
  <div class="navbar-example">
    <ul class="nav">
      <li><a href="#a">a</a></li>
      <li><a href="#b">b</a></li>
      <li><a href="#c">c</a></li>
    </ul>
  </div>
  <div class="navbar-content">
    <p id="a">blanblanblanblan</p>
    <p id="b">blanblanblanblan</p>
    <p id="c">blanblanblanblanblan</p>
  </div>
</body>
```

JS
```js
$('body').scrollspy({ target: '.navbar-content' })
```


## 页面效果

滚到到第一个导航条下的内容
![](http://img.teamkn.com/i/tGFyl1Ja.png)

滚到到第二个导航条下的内容
![](http://img.teamkn.com/i/M9pcCdJJ.png)