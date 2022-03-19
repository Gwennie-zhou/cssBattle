## **#23Boxception**

![image](https://github.com/Gwennie-zhou/cssBattle/blob/master/4_Display/images/%2323Boxception.png)

```html
<div class="outer">
  <div class="middle">
    <div class="inner"></div>
  </div>
</div>
<style>
  body {
    background: #F3AC3C;
    display:flex;
    justify-content: center;
    align-items: center;
  }
  .outer {
    position: relative;
    width: 200px;
    height: 200px;
    background: #1A4341;
  }
  .middle {
    position: absolute;
    bottom: 0;
	width: 100px;
    height: 100px;
    background: #998235;
  }
  .inner {
    position: absolute;
    bottom: 0;
    right:0;
	width: 50px;
    height: 50px;
    background: #F3AC3C;
  }
</style>
```

