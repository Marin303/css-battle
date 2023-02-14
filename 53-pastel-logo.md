![](https://cssbattle.dev/targets/53@2x.png)

```HTML
<div></div>
<style>
body{
  background: #19191A;
}
  div{
    background:#4F77FF;
    width:150px;
    height:150px;
    border-radius:50%;
    position:absolute;
    top:50px;
    left:50%;
    transform:translateX(-50%);
    overflow:hidden;
  }
  :before{
    content:'';
    position:absolute;
    width:75px;
    height:125px;
    right:50%;
  }
  div:before{
    background:#9AD5FF;
    top:50%;
  }
  body:before{
    background:#F9E492;
    top:125px;
  }
</style>

```
