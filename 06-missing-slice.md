![](https://cssbattle.dev/targets/6.png)

```HTML
<div></div>
<div></div>
<div></div>
<style>
  *{
    margin:0;
    position: absolute;
  }
  body{
    background: #E3516E;
  }
  div:first-child {
    width: 100px;
    height: 100px;
    background: #51B5A9;
    left:100px;
    top:50px;
    border-top-left-radius:100% ;
  }
  div:nth-child(2){
    width: 100px;
    height: 100px;
    background: #FADE88;
    left:200px;
    top:50px;
    border-top-right-radius:100% ;
  }
  div:nth-child(3){
    width: 100px;
    height: 100px;
    background: #F7F3D7;
    left:100px;
    top:150px;
    border-bottom-left-radius:100% ;
  }
</style>
```
