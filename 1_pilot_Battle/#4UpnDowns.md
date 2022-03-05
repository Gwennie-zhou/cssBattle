## **#4UpnDowns**

![image](https://github.com/Gwennie-zhou/cssBattle/blob/master/1_pilot_Battle/images/%234UpnDowns.png)

```html
<div class="box left"></div>
<div class="box center"></div>
<div class="box right"></div>
<style>
  body {
    background-color:#62306D;
  }
  .box {
	position: absolute;
    width: 100px;
    height: 100px;
    background: #F7EC7D;
    border-radius: 0 0 50% 50%;
  }
  .left {
    bottom: 50px;
    left:50px;
  }
  .center {
	top: 50px;
    left: 150px;
    transform: rotate(180deg);
  }
  .right {
	right: 50px;
    bottom: 50px;
  }
</style>
```

