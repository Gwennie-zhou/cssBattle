## **#26Smiley**

![image](https://github.com/Gwennie-zhou/cssBattle/blob/master/4_Display/images/%2326Smiley.png)

```html
<div class="circle left"></div>
<div class="circle right"></div>
<div class="circle below"></div>
<style>
  body {
    background: #6592CF;
  }
  .circle {
    position: absolute;
    width: 120px;
    height: 60px;
    box-sizing: border-box;
    border: 20px solid #060F55;
    border-bottom: 0;
    border-radius: 60px 60px 0 0 ;
  }
  .left { top: 40px; left:40px;}
  .right { top: 40px;right:40px;}
  .below{
    bottom: 40px;
    left: 140px;
    transform: rotate(180deg);
  }
</style>
```

