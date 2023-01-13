![](https://cssbattle.dev/targets/22@2x.png)
```HTML
<div></div>
<style>
  body {
    background: #F5D6B4;
    margin: 0;
    position:relative;
    box-sizing:border-box;
  }
  
  div {
    width: 100px;
    height: 100px;
    background: #D86F45;
    border-radius: 50%;
    top: 120px;
    left: 110px;
    transform: translate(-10%, -5%);
    position: absolute; 
  }
  div:before {
    content: '';
    display: block;
    width: 100px;
    height: 100px;
    background: #D86F45;
    border-radius: 50%;
    position: absolute;
    top: -30px;
    left: 80px;
  }
    div:after {
    content: '';
    display: block;
    width: 150px;
    height: 50px;
    background: #D86F45;
    border-radius: 0 40px 40px 0;
    position: absolute;
    top: 50px;
    left: 50px;
  }
 
</style>
```
