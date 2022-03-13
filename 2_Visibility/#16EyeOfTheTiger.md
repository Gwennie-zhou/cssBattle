## **#16EyeOfTheTiger**

![image](https://github.com/Gwennie-zhou/cssBattle/blob/master/2_Visibility/images/%2316EyeOfTheTiger.png)

```html
<div class="wrap">
  <div class="circle"></div>
</div>
<style>
  body {
    display: flex;
    justify-content: center;
    align-items: center;
    background: #0B2429;
  }
  .wrap {
    position: relative;
    width:200px;
    height: 200px;
    background: #998235;
    border-radius: 0 50%;
    transform: rotate(-45deg);
  }
  .circle {
    position: absolute;
    top:50%;
    left:50%;
    transform: translate(-50%,-50%);
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background: #0B2429;
    box-shadow: 0 0 0 45px #F3AC3C, 0 0 0 65px #0B2429;
  }
</style>
```

