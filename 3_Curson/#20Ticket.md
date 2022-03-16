## **#20Ticket**

![image](https://github.com/Gwennie-zhou/cssBattle/blob/master/3_Curson/images/%2320Ticket.png)

```html
<div class="wrap">
  <div class="l"></div>
  <div class="r"></div>
  <div class="circle c1"></div>
  <div class="circle c2"></div>
  <div class="circle c3"></div>
  <div class="circle c4"></div>
  <div class="circle c5"></div>
  <div class="circle c6"></div>
 </div>
<style>
  body {
    background: #62306D;
    display: flex;
    justify-content:center;
    align-items: center;
  }
  .wrap {
    display: flex;
    position: relative;
  }
  .l {
    width: 140px;
    height: 100px;
    background: #F7EC7D;
  }
  .r {
    width: 60px;
    height: 100px;
    background: #E38F66;
  }
  .circle {
    position: absolute;
    width:40px;
    height: 40px;
    border-radius: 50%;
    background: #62306D;
  }
  .c2,.c5 {
    left: 130px;
    width:20px;
    height: 20px;
    border-radius: 50%;
  }
  .c2 { top: -10px;}
  .c5 { bottom: -10px;}
  .c1,.c3 { top: -20px; }
  .c4,.c6 { bottom: -20px;}
  .c1,.c4 { left: -20px;}
  .c3,.c6 { right: -20px;}

</style>
```

