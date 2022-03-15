## **#18Matrix**

![image](https://github.com/Gwennie-zhou/cssBattle/blob/master/2_Visibility/images/%2318Matrix.png)

```html
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<style>
  * {
    margin: 0;
  }
  body {
    height: 300px;
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    background: #5C434C;
  }
  div {
    margin: 10px 10px;
    width: 80px;
    height: 80px;
    background: #F09462;
    border-radius:  100% 0 0 0;
  }
  div:nth-child(even) {
    background: #F5D6B4;
  }
</style>
```

