![](https://cssbattle.dev/targets/40@2x.png)

```HTML
<div></div>
<style>
  body{
    background:#6592CF;
    position: relative;
  }
  div {
    width:100px;
    height:100px;
    border:50px solid #243D83;
    border-left:40px solid transparent;
    border-radius: 50%;
    transform: rotate(40deg);
    position: absolute;
    top:46px;
    left:106px
  }
  div:after{
    content:'';
    display:block;
    width:48px;
    height:110px;
    background:#243D83;
    transform:rotate(-40deg);
    position: absolute;
    left:-50px;
    top:15px;
    border-radius: 0 0 0 15px;
  }
  
</style>

```
