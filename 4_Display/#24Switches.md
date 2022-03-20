## **#24Switches**

![image](https://github.com/Gwennie-zhou/cssBattle/blob/master/4_Display/images/%2324Switches.png)

```html
<div class="wrap">
  <div class="circle"></div>
</div>
<div class="wrap reverse">
  <div class="circle"></div>
</div>
<style>
  body {
    background: #62306D;
    display: flex;
    justify-content: center;
  }
  .wrap {
    position: relative;
    width: 100px;
    height: 150px;
    background: #AA445F;
    border-radius: 100px;
    margin-top: 42px;
  }
  .circle {
    position: absolute;
    bottom: 0;
	width: 100px;
    height: 100px;
    background: #F7EC7D;
    border-radius: 50%;
  }
  .wrap.reverse {
    transform: rotate(180deg);
    background: #E38F66;
    margin-left: 40px;
    margin-top: 92px
  }
</style>
```

