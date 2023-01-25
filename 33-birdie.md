![](https://cssbattle.dev/targets/33.png)

```HTML
<div></div>
<span></span>
<style>
  body{
    background: #1A4341;
    margin:0;
    position: relative;
  }
  div {
    width: 100px;
    height: 100px;
    background: #F3AC3C;
    border-radius: 0 100px 0 0;
    position: absolute;
    top: 50px;
    left: 200px;
  }
  span{
    width: 75px;
    height: 145px;
    background: #998235;
     border-radius: 100px 0 0 100px;
    position: absolute;
    top: 74px;
    left: 125px;
  }
  span:after{
    content: "";
    display: block;
    width: 30px;
    height: 30px;
    background: #0B2429;
    border-radius: 50%;
    position: absolute;
    top: 30px;
    left:30px;
  }
</style>
```
