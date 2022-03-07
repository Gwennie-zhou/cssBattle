## **#11EyeOfSauron**

![image](https://github.com/Gwennie-zhou/cssBattle/blob/master/1_pilot_Battle/images/%2311EyeOfSauron.png)

```html
<div class="wrap">
  <div class="half-circle lc"></div>
  <div class="circle"></div>
  <div class="half-circle rc"></div>
</div>
<style>
  * {
    margin: 0;
  }
  body {
    display: flex;
    justify-content: center;
    background: #191210;
  }
  .wrap {
    margin: 30px ;
    display: flex;
    justify-content: space-around;
    align-items: center;
    width: 360px;
  }
  .circle {
    width: 50px;
    height: 50px;
    background: #84271C;
    border-radius: 50%;
    box-shadow: 0 0 0 25px #191210, 0 0 0 45px #ECA03D;
  }
  .half-circle {
    width: 100px;
    height: 50px;
    box-sizing: border-box;
    border: 20px solid #ECA03D;
    border-top: 0;
    border-radius: 0 0 100px 100px;
  }
  .lc {
	margin-top: 35px; 
  }
  .rc {
    margin-top: -40px;
    margin-left: 5px;
    transform: rotate(180deg);
  }
</style>
```

