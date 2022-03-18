## **#22Cloud**

![image](https://github.com/Gwennie-zhou/cssBattle/blob/master/4_Display/images/%2322Cloud.png)

```html
<div class="wrap">
  <div class="left"></div>
  <div class="right"></div>
  <div class="bottom"></div>
</div>
<style>
  body {
    display: flex;
    justify-content: center;
    align-items: center;
    background: #F5D6B4;
  }
  .wrap {
    position: relative;
    width: 200px;
    height: 130px;
  }
  .bottom {
    position: absolute;
    bottom: 0;
    right: 0;
    width: 150px;
    height: 50px;
    border-radius: 0 100px 100px 0;
    background: #D86F45;
  }
  .left {
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100px;
    height:100px;
    border-radius: 50%;
    background: #D86F45;
  }
  .right {
    position: absolute;
    bottom: 30px;
    right: 20px;
    width: 100px;
    height:100px;
    border-radius: 50%;
    background: #D86F45;
  }
</style>
```

