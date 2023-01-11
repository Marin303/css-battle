![](https://cssbattle.dev/targets/20@2x.png)

```HTML
<div class="one"></div>
<div class="two"></div>
<span></span>
<style>
  body {
    background: #62306D;
    margin: 0;
    position: relative;
  }
  .one {
    width: 140px;
    height: 100px;
    background: #F7EC7D;
    position: absolute;
    top: 100px;
    left: 100px;
  }
  .one:before, .one:after {
    content: '';
    display: block;
    width: 30px;
    height: 30px;
    background: #62306D;
    position: absolute;
    left: -10px;
    border-radius: 50%;
  }
  .one:before{
    top: -10px;
  }
  .one:after {
    bottom:-10px;
  }
  .two {
    width: 60px;
    height: 100px;
    background: #E38F66;
    position: absolute;
    top: 100px;
    right: 100px;
  }
  .two:before, .two:after {
    content: '';
    display: block;
    width: 20px;
    height: 20px;
    background: #62306D;
    position: absolute;
    left: -10px;
    border-radius: 50%;
  }
  .two:before{
    top: -10px;
  }
  .two:after {
    bottom: -10px;
  }
  span {
    width: 30px;
    height: 30px;
    border-radius: 50%;
    background: #62306D;
    position: absolute;
    top: 90px;
    left: 280px;
  }
  span:after {
    content: '';
    display: block;
    width: 30px;
    height: 30px;
    background: #62306D;
    position: absolute;
    bottom:-90px;
    border-radius: 50%;
  }
</style>
```
