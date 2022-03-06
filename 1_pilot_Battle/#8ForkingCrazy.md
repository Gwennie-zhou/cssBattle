## **#8ForkingCrazy**

![image](https://github.com/Gwennie-zhou/cssBattle/blob/master/1_pilot_Battle/images/%238ForkingCrazy.png)

```html
<div class="wrap">
  <div class="sticks">
    <div class="t1"></div>
    <div class="t1 down"></div>
    <div class="t1"></div>
    <div class="t1 down"></div>
    <div class="t1"></div>
    <div class="t1 down"></div>
    <div class="t1"></div>
  </div>
  <div class="center"></div>
  <div class="handle"></div>
</div>
<style>
  * {
    margin: 0;
  }
  body {
    background: #6592CF;
    display: flex;
    justify-content: center;
    align-items: flex-end;
  }
  .wrap {
    width: 140px;
    height: 250px;
  }
  .sticks {
    display: flex;
    justify-content: space-between;
    height: 110px;
  }
  .t1 {
    width: 20px;
    background: #060F55;
    border-radius: 80px 80px 0 0;
 }
  .down {
    transform: rotate(180deg);
    background: #6592CF;
  }
  .center {
    height: 90px;
    border-radius: 0 0 80px 80px;
    background: #060F55;
  }
  .handle {
    width: 20px;
    height: 50px;
    background: #060F55;
    margin: 0 auto;
  }

</style>
```

