## **#14WebMakerLogo**

![image](https://github.com/Gwennie-zhou/cssBattle/blob/master/2_Visibility/images/%2314WebMakerLogo.png)

```html
<div class="triangle f">
  <div class="triangle s"></div>
</div>
<div class="triangle f right">
  <div class="triangle s"></div>
</div>

<style>
body {
  display: flex;
  justify-content: center;
  align-items: center;
  background: #F2F2B6;
}
.triangle {
  width:0;
  height:0;
  border-top: 130px solid #FF6D00;
  border-left: 75px solid transparent;
  border-right: 75px solid transparent;
}
.f {
  position: relative;
}
.s {
  position: absolute;
  top: -130px;
  left: -55px;
  z-index: -1;
  border-top: 130px solid #FD4602;
}
.right {
  transform: rotate(180deg);
  margin-left: -20px;
 }
</style>
```

