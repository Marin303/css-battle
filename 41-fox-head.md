![](https://cssbattle.dev/targets/41@2x.png)

```HTML
<div>
</div>
<style>
  body{
    background:#293462;
    margin:0;
    margin-top:80px
  }
  div {
    width: 50px;
    height: 140px;
    background: #FE5F55;
    border-radius: 0 40px 0 0;
    position:absolute;
    -webkit-box-reflect: right;
    right:200px;
    
  }
  div:before,div:after{
  content:'';
  display:block;
  position:absolute;
  border-radius: 50%;
  background: #293462;
  }
  
  div:after{
  height:30px;
  width:30px;
  bottom:50px;
  left:15px;
}
  div:before{
  height:72px;
  width:71px;
  bottom:-30px;
  left:-20px;
}


</style>

```
