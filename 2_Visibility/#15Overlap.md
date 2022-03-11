## **#15Overlap**

![image](https://github.com/Gwennie-zhou/cssBattle/blob/master/2_Visibility/images/%2315Overlap.png)

```html
<div></div>
<div>
  <div class="center"></div>
</div>

<style>
  body {
    background:#09042A;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  div {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    background: #7B3F61;
  }
  div:nth-child(2){
    background: #E78481;
    margin-left:-50px;
    overflow: hidden;
  }
  .center {
    margin-left:-100px;
    background: #09042A;
  }
</style>

```

