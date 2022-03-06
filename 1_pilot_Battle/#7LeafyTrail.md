## **#7LeafyTrail**

![image](https://github.com/Gwennie-zhou/cssBattle/blob/master/1_pilot_Battle/images/%237LeafyTrail.png)

```html
<div class="wrap">
    <div class="l"></div>
    <div class="l"></div>
    <div class="l"></div>
</div>
<style>
  body {
    background: #0B2429;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .wrap {
    width:250px;
    height: 150px;
  }
  .l {
    position: absolute;
    width: 150px;
    height: 150px;
    background: #1A4341;
    border-radius: 67% 0;
  }
  .l:nth-child(2) {
    background: #998235;
    left:120;
  }
  .l:nth-child(3) {
    background: #F3AC3C;
    right: 75px;
  }
</style>
```

