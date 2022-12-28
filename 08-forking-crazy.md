![](https://cssbattle.dev/targets/8.png)

```HTML 
<div class="bottom"></div>
<div class="mid"></div>
<div class="top">
  <span></span>
  <span></span>
  <span></span>
  <span></span>
  <span></span>
  <span></span>
  <span></span>
</div>
<style>
  body{
    background: #6592CF;
  }
  .bottom {
    width:20px;
    height:60px;
    background: #060F55; 
    position:absolute;
    bottom:0;
    left: 50%;
    transform: translateX(-50%);
  }
  .mid {
    width:140px;
    height:140px;
    border-radius: 50%;
    background: #060F55; 
    position:absolute;
    bottom:50px;
    left:50%;
    transform: translateX(-50%);
  }
  .top {
    display:flex;
    position:absolute;
    width: 140px;
    height: 140px;
    left: 50%;
    transform: translateX(-50%);
    top: 50px;
  }
  span {
    width: calc(100%/7);
  }
  span:nth-child(odd){
    background: #060F55;
    height: 130px;
    border-radius: 20px 20px 0 0;
  }
  span:nth-child(even){
    background: #6592CF;
    height: 110px;
    border-radius: 0 0 20px 20px;
  }
  
</style>

```
