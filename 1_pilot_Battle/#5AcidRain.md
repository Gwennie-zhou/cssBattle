## **#5AcidRain**

![image](https://github.com/Gwennie-zhou/cssBattle/blob/master/1_pilot_Battle/images/%235AcidRain.png)

```html
<div class="box bottom"></div>
<div class="box center"></div>
<div class="box top"></div>
<style>
  body {
    background: #0B2429;
  }
  .box {
    position: absolute;
    width: 120px;
    height: 120px;
    background: #F3AC3C;
  }
  .bottom {
    bottom: 30px;
    left: 80px;
    z-index: 3;
    border-radius: 50% 0 50% 50%;
  }
  .center {
    bottom: 90px;
    left: 140px;
    z-index: 2;
    border-radius: 50% 0 50% 50%;
    background: #998235;
  }
  .top {
    top: 30px;
    right: 80px;
    z-index: 1;
	border-radius: 50%;
  }
</style>
```

