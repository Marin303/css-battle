![](https://cssbattle.dev/targets/24@2x.png)

```HTML
<div></div>
<span></span>
<style>
  body{
    background:#62306D;
    margin: 0;
    box-sizing:border-box;
    position: relative;
  }
  div {
    width: 100px;
    height: 100px;
    background: #F7EC7D;
    border-radius: 50%;
    position: absolute;
    top: 100px;
    left: 80px;
  }
  div:after {
    content: '';
    display:block;
    width: 100px;
    height: 150px;
    background: #AA445F;
    border-radius: 50px;
    position: absolute;
    top:-50px;
    z-index: -1;
  }
  span {
    width: 100px;
    height: 100px;
    background: #F7EC7D;
    border-radius: 50%;
    position: absolute;
    top: 100px;
    left: 220px;
  }
  span:before {
    content: '';
    display:block;
    width: 100px;
    height: 150px;
    background: #E38F66;
    border-radius: 50px;
    position: absolute;
    z-index: -1;
  }
</style>
```
