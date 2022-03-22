## **#25Blossom**

![image](https://github.com/Gwennie-zhou/cssBattle/blob/master/4_Display/images/%2325Blossom.png)

```html
<div class="left">
  <div class="top"></div>
  <div class="below"></div>
</div>
<div class="right">
  <div class="top"></div>
  <div class="below"></div>
</div>
<style>
  body {
    display: flex;
    justify-content: center;
    align-items: center;
    background: #998235;
  }
  .top {
    width: 80px;
    height: 100px;
    background: #1A4341;
    border-radius: 0 50px;
  }
  .below {
    margin-top: 20px;
    width: 80px;
    height: 60px;
    background: #F3AC3C;
    border-radius: 0 50px;
  }
  .right {
    transform: rotateX(180deg);
    margin-left: 20px;
  }
</style>
```

