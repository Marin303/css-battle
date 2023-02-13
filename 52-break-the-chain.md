![](https://cssbattle.dev/targets/52@2x.png)

```HTML
<div><p></p></div>
<div><span></span></div>
<div><p></p></div>
<div></div>
<div></div>
<div></div>
<div></div>
<style>
body{
  background:#6592CF;
  display:flex;
  justify-content:center;
  align-items:center;
}  
  div {
    width: 10px;
    height: 50px;
    background: #243D83;
    margin:30px 17.5px 0px ;
    position:relative;
  }
  div:nth-child(3){
    margin-right:47.5px;
  }
  div:after{
    content:'';
    display:block;
   position:absolute;
  top:-10px;
    left:-4px;
    width:20px;
    height:20px;
    border-radius:50%;
    background-color:#243D83;
  }
  p{
    position:absolute;
    top:-35px;
    left:-15px;
    width:40px;
    height:40px;
    border-radius:50%;
    background-color:#EEB850;
    z-index:-1;
  }
  span{
     position:absolute;
    top:-40px;
    left:-24px;
    width:60px;
    height:60px;
    border-radius:50%;
    background-color:#EEB850;
    z-index:-1;
  }
</style>

```
