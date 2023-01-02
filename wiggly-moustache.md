![](https://cssbattle.dev/targets/12.png)

```HTML
<div>
<span></span>
<span></span>
</div>
<style>
  * {
    box-sizing: border-box;
  }
  body{
    background: #F5D6B4;
    margin:0;
  }
  div {
    width: 100px;
    height: 50px;
    border: 20px solid #D86F45;
    border-radius: 110px 110px 0 0;
    border-bottom: 0;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50px)
  }
  span {
    width: 100px;
    height: 50px;
    border: 20px solid #D86F45;
    border-radius: 0 0 110px 110px;
    border-top: 0;
    position: absolute;
    top: calc(50% + 10px)
  }
  span:before{
    content:'';
    background: #D86F45;
    width: 20px;
    height: 20px;
    border-radius: 50%;
    position:absolute;
    top: -10px;
  
    
  }
  span:nth-child(1){
    left: 0 ;
    transform: translate(-100%, 0)
  }
  span:nth-child(1):before{
    left: -20px;
    
  }
  span:nth-child(2){
    right: 0;
    transform: translate(100%, 0)
  }
  span:nth-child(2):before{
    left:60px;
  }
</style>
```
