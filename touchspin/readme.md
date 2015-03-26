# bootstrap-touchspin

## 网址
https://github.com/istvan-ujjmeszaros/bootstrap-touchspin

## 前端代码

HTML
```html
<input id="demo1" type="text" value="55" name="demo1">
```

JS
```js
  $("input[name='demo1']").TouchSpin({
        min: 0,
        max: 100,
        step: 0.1,
        decimals: 2,
        boostat: 5,
        maxboostedstep: 10,
        postfix: '%'
    });
```

![](http://img.teamkn.com/i/s6SyJmrZ.png)

## 绑定事件
```js
$("input[name='demo1']").on('touchspin.on.startspin',function(){
  // Triggered when the spinner starts spinning upwards or downwards.
});
```