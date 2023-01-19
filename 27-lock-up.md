![](https://cssbattle.dev/targets/27@2x.png)
```HTML
<div></div>
<style>
  body{
    background:#E38F66;
    margin: 0;
    position: relative;
  }
  div {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    background: #AA445F;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%)
  }
  div:after{
    content:'';
    display:block;
    width: 80px;
    height: 80px;
    border: 30px solid #F7EC7D;
    border-top-color: transparent;
    border-bottom-color: transparent;
    border-radius: 50%;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%) rotate(-45deg);
  }
</style>

```
