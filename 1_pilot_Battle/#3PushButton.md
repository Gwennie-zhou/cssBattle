## **#3PushButton**

![image](https://github.com/Gwennie-zhou/cssBattle/blob/master/1_pilot_Battle/images/%233PushButton.png)

```html
<div class="rect">
    <div class="circle"></div>
</div>

<style>
  * {
    background: #6592CF;
  }
  .rect {
    margin: 75px 42px;
    width: 300px;
    height: 150px;
    background: #243D83;
    overflow: hidden; /** Trigger BFC and prevent margin collapsing **/
  }
  .circle {
    border-radius: 25px;
    width: 50px;
    height: 50px;
    background: #EEB850;
    margin: 50px auto;
    box-shadow: 0 0 0 50px #243D83, 0 0 0 100px #6592CF;
  }
</style>
```

