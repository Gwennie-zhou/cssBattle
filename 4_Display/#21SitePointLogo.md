## **#21SitePointLogo**

![image](https://github.com/Gwennie-zhou/cssBattle/blob/master/4_Display/images/%2321SitePointLogo.png)

```html
<div class="wrap">
  <div class="long"></div>
  <div class="short"></div>
</div>
<div class="wrap reverse">
  <div class="long"></div>
  <div class="short"></div>
</div>
<style>
  body {
    background: #222;
  }
  .wrap {
    display: flex;
    flex-direction: column;
    transform: rotate(45deg);
    position: absolute;
    left: 148px;
    top: 75px;
  }
  .long {
    width: 30px;
    height: 100px;
    background: #F2994A;
    border-bottom-left-radius: 10px;
  }
  .short {
    width: 60px;
    height: 30px;
    background: #F2994A;
    border-top-right-radius: 5px;
    margin-top: -30px;
    margin-left: 20px;
  }
  .wrap.reverse {
    transform: scale(-1, -1) rotate(45deg);
    top: 123px;
    left: 170px;
  }
  .reverse .long, 
  .reverse .short {
    background: #2D9CDB;
  }
</style>
```

