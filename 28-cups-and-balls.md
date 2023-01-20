![](https://cssbattle.dev/targets/28@2x.png)
```HTML
<div>
  <div></div>
  <div></div>
  <div></div>
</div>
<span>
  <span></span>
  <span></span>
  <span></span>
</span>
<style>
  body{
    background:#1A4341;
    margin:0;
    position: relative;
  }
  div {
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background: #998235;
    position: absolute;
    top: 90px;
    left: 70px;
  }
  div > div:first-child{
   position: absolute;
    top: 70px;
    left: 70px; 
  }
  div > div:nth-of-type(2){
   position: absolute;
    top: 70px;
    left: 140px; 
    background: #F3AC3C;
  }
  div > div:nth-of-type(3){
   position: absolute;
    top: 0px;
    left: 210px; 
    background: #F3AC3C;
  }
  span {
    width: 50px;
    height: 50px;
    border-radius: 50% 50% 0% 0%;
    background: #F3AC3C;
    position: absolute;
    top: 90px;
    left: 140px;
  }
  span > span:first-child{
    transform: scale(1, -1);
    background:#998235;
    top:70px;
  }
  span > span:nth-child(2){
    left:-70px;
    top:70px;
    transform: scale(1, -1);
  }
  span > span:nth-child(3){
   top:0px;
    left:70px;
    background:#998235;
  }
</style>
```
