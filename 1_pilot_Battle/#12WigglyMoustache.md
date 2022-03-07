## **#12WigglyMoustache**

![image](https://github.com/Gwennie-zhou/cssBattle/blob/master/1_pilot_Battle/images/%2312WigglyMoustache.png)

```html
<div class="wrap">
  <div class="half"></div>
  <div class="half"></div>
  <div class="half"></div>
</div>
<style>
  body {
	background: #F5D6B4;
  }
  .wrap {
    margin: 120px auto;
    display: flex;
  }
  .half {
    width: 60px;
    height: 30px;
    border-radius: 0 0 50px 50px;
    border: 20px solid #D86F45;
    border-top: 0;
    background: #F5D6B4;
  }
  .half:nth-child(1) {
    position: relative;
    margin-top: 30px;
    margin-left: 60px;
  }
  .half:nth-child(2) {
    margin-top: -20px;
    margin-left:-20px;
    transform: rotate(180deg);
  }
  .half:nth-child(3) {
    position: relative;
    margin-top: 30px;
    margin-left: -20px;
  }
  .half:nth-child(1)::before,.half:nth-child(3)::before {
    content: "";
    width: 20px;
    height: 20px;
    position: absolute;
    top: -10px;
    background:#D86F45;
    border-radius: 50px;
  }
  .half:nth-child(1)::before {
    left: -20px;
  }
  .half:nth-child(3)::before {
    right:-20px;
  }
</style>

```

