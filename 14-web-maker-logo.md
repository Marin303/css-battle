![](https://cssbattle.dev/targets/14@2x.png)
```HTML
<div class="left"></div>
<div class="left2"></div>
<div class="right"></div>
<div class="right2"></div>
<style>
  body{
    margin:0;
    background: #F2F2B6;
    position: relative;
  }
  .left {
    width: 0;
    height: 0;
    border-left: 82px solid transparent;
    border-right: 82px solid transparent;
    border-bottom: 130px solid #FF6D00;
    transform: rotate(180deg);
    position: absolute;
    top:85px;
    left:55px;
  }
  .left2 {
    width: 0;
    height: 0;
    border-left: 82px solid transparent;
    border-right: 82px solid transparent;
    border-bottom: 130px solid #FD4602;
    transform: rotate(180deg);
    position: absolute;
    top:85px;
    left:75px;
    z-index:-1;
  }
   .right {
    width: 0;
    height: 0;
    border-left: 82px solid transparent;
    border-right: 82px solid transparent;
    border-bottom: 130px solid #FD4602;
    position: absolute;
    top:85px;
    right:65px;
  }
  .right2 {
    width: 0;
    height: 0;
    border-left: 82px solid transparent;
    border-right: 82px solid transparent;
    border-bottom: 130px solid #FF6D00;
    position: absolute;
    top:85px;
    right:45px;
    z-index:-1;
  }
</style>
```
