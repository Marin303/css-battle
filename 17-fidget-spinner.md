![](https://cssbattle.dev/targets/17@2x.png)
```HTML
<div class="one"></div>
<div class="square"></div>
<div class="two"></div>
<span></span>

<style>
  body{
    background: #09042A;
    margin: auto;
    display: flex;
    box-sizing: border-box;
  }
  .one ,.two {
    width: 60px;
    height: 60px;
    background: #09042A;
    border: 10px solid #E78481;
    border-radius: 50%;
    margin: 110px 0 0 100px;
  }
 .two{
  margin-left: 40px;
  }
  .square {
    width: 50px;
    height: 40px;
    background: #E78481;
    position:absolute;
    top: 130px;
    left: 175px;
  }
  span {
    border: 10px solid #09042A;
    background:#F5BB9C;
    width: 60px;
    height: 60px;
    border-radius: 50%;
    position:relative;
    top: 20%;
    left: -36%;
    transform: translate(5px);
  }
   span:after {
    content:'';
    display:block;
    border: 10px solid #09042A;
    background:#F5BB9C;
    width: 60px;
    height: 60px;
    border-radius: 50%;
    position:relative;
    top: 150%;
    left: -35%;
    transform: translateX(10px);
  }
    
</style>
```
