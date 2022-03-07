## **#10CloakedSpirits**

![image](https://github.com/Gwennie-zhou/cssBattle/blob/master/1_pilot_Battle/images/%2310CloakedSpirits.png)

```html
<div class="wrap">
  <div class="circle lc"></div>
  <div class="circle rc"></div>
</div>
<div class="center">
    <div class="circle cc"></div>
</div>
<style>
  * {
    margin: 0;
  }
  body {
    background: #62306D;
    display: flex;
    justify-content: center;
    align-items: flex-end;
  }
  .wrap {
    position: relative;
    width: 300px;
    height: 100px;
    background: #F7EC7D;
  }
  .circle {
    position: absolute;
    top: -30px;
    width: 60px;
    height: 60px;
    background: #E38F66;
    border-radius: 50%;
    box-shadow: 0 0 0 20px #AA445F;
  }
  .lc {
    left: 19px;
  }
  .rc {
    right: 19px;
  }
  .center {
    position: absolute;
    width: 100px;
    height: 200px;
    background: #F7EC7D;
  }
  .cc {
    position: absolute;
    left:20px;
    background: #AA445F;
    box-shadow: 0 0 0 20px #E38F66;
  }
</style>
```

