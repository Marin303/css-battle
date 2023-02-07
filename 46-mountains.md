![](https://cssbattle.dev/targets/46@2x.png)

```HTML
<div>
<p></p>
</div>
<style>
  body{
    background:#293462;
    display:flex;
    justify-content:center;
  }
  div {
    width: 200px;
    height: 200px;
    border-radius:50%;
    background: #FFF1C1;
    margin:auto;
    overflow:hidden;
  }
  p{
    background:#FE5F55;
    width:150px;
    height:150px;
    margin-top:90px;
    margin-left:65px;
    transform:rotate(45deg);
    position: relative;
  }
p:before{
    content:'';
    display:block;
    background:#FE5F55;
    width:70px;
    height:70px;
    position: absolute;
    left:-30px;
    bottom:-48px;
}
  
</style>



```
