![](https://cssbattle.dev/targets/21.png)
```HTML
<div class="orange"></div>
<div class="blue"></div>
<div class="orange1"></div>
<div class="blue1"></div>
<style>
  body {
    background: #222;
    margin: 0;
    position:relative;
  }
  .orange {
    width: 30px;
    height: 100px;
    background: #F2994A;
    position: absolute;
    top: 60px;
    left: 160px;
    transform: translate(-10%)rotate(45deg);
    border-bottom-left-radius: 15px;
  }
   .orange1 {
    width: 30px;
    height: 70px;
    position:absolute;
    background:#F2994A;
    top: 120px;
    left: 160px;
    transform: translate(-30%) rotate(-45deg);;
    border-top-left-radius: 15px;
    border-bottom-right-radius: 5px;
  }
  .blue{
    width: 30px;
    height: 100px;
    position: absolute;
    top: 140px;
    left: 210px;
    background: #2D9CDB;
    transform: translate(5%) rotate(45deg);
    border-top-right-radius: 15px;
  }
 
  .blue1 {
    width: 30px;
    height: 70px;
    position:absolute;
    background:#2D9CDB;
    top: 110px;
    left: 200px;
    border-bottom-right-radius: 15px;
    transform: translate(55%) rotate(-45deg);
    border-top-left-radius: 5px;
  }
</style>
```
