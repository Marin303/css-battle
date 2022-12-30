![](https://cssbattle.dev/targets/10.png)

```HTML
<div></div>
<div></div>
<div></div>
<style>
  body{
    background: #62306D;
    display: flex;
    align-items:flex-end;
    justify-content: center;
    margin:0;
  }
  div {
    width: 100px;
    height: 100px;
    background: #F7EC7D;
    position: relative;
  }
  div:nth-of-type(2){
    height: 200px;
  }
   div:nth-of-type(2):after{
    background:#AA445F;
    box-shadow: 0 0 0 20px #E38F66;
  }
  div:after {
    display: block;
    content: '';
    position: absolute;
    left: 50%;
    top: 0;
    transform: translate(-50%, -50%);
    background: #E38F66;
    width: 60px;
    height: 60px;
    border-radius: 50%;
    box-shadow: 0 0 0 20px #AA445F;
  }
</style>
```
