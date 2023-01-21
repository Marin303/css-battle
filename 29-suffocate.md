![](https://cssbattle.dev/targets/29@2x.png)

```HTML
<div></div>
<span></span>
<style>
body{
  background:#F3AC3C;
  margin:0;
  position:relative;
}
  div {
    width: 200px;
    height: 200px;
    background: #1A4341;
    position: absolute;
    top:50px;
    left:100px;
  }
  div:before{
    content:'';
    display:block;
    background:#F3AC3C;
    width:200px;
    height:200px;
    border-radius:50%;
    margin:100px;
  }
  div:after{
    content:'';
    display:block;
    background:#F3AC3C;
    width:200px;
    height:200px;
    border-radius:50%;
    margin:-100px;
    position:absolute;
    top: 0px;
  }
  span {
    width: 200px;
    height: 200px;
    background:#F3AC3C;
    position: absolute;
    top:150px;
    left:0px;
    border-radius:50%;
  }
    span:after{
    content:'';
    display:block;
    background:#F3AC3C;
    width:200px;
    height:200px;
    border-radius:50%;
    position:absolute;
    top: -200px;
    left:200px;
  }
</style>
```
