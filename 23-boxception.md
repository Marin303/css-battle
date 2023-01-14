![](https://cssbattle.dev/targets/23@2x.png)
```HTML
<div></div>
<style>
  body {
    background:#F3AC3C;
    margin: 0;
    position: relative;
  }
  div {
    width: 200px;
    height: 200px;
    background: #1A4341;
    position: absolute;
    top: 50px;
    left: 100px;
  }
  div:before {
    content:'';
    display: block;
    width: 100px;
    height: 100px;
    background: #998235;
    position: absolute;
    bottom: 0;
  }
  div:after {
    content:'';
    display: block;
    width: 50px;
    height: 50px;
    background: #F3AC3C;
    position: absolute;
    bottom: 0;
    left:50px;
  }
</style>
```
