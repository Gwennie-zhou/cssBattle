## **#19Cube**

![image](https://github.com/Gwennie-zhou/cssBattle/blob/master/3_Curson/images/%2319Cube.png)

```html
<div class="l"></div>
<div class="c"></div>
<div class="r"></div>
<style>
  body {
    background: #0B2429;
  }
  .c {
    position: absolute;
    bottom: 65px;
    left: 150px;
    transform: rotate(45deg);
    width: 100px;
    height: 100px;
    background: #F3AC3C;
  }
  .l,.r {
    position: absolute;
    top: 80px;
    left: 130px;
    transform: skewY(-45deg);
    width: 70px;
    height: 70px;
    background: #998235;
  }
  .r {
    top: 80px;
    left: 200px;
    transform: skewY(45deg);
    background: #1A4341;
  }
</style>
```

