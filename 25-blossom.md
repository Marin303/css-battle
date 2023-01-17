![](https://cssbattle.dev/targets/25@2x.png)
```HTML
<div></div>
<div></div>
<span></span>
<span></span>
<style>
body {
  background:#998235;
  margin: 0;
  position: relative;
}
  div {
    width: 80px;
    height: 100px;
    border-radius: 0 50px 0 50px;
    background: #1A4341;
    position: absolute;
    top: 60px;
    left: 110px;
  }
  div:nth-of-type(2){
    top: 140px;
    left: 210px;
    transform: scale(-1, 1);
  }
  span {
    width: 80px;
    height: 60px;
    border-radius: 0 50px 0 50px;
    background: #F3AC3C;
    position: absolute;
    top: 180px;
    left: 110px;
  }
  span:nth-of-type(2){
    top: 60px;
    left: 210px;
    transform: scale(-1, 1);
  }
</style>
```
