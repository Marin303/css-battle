![](https://cssbattle.dev/targets/59@2x.png)

```HTML
<div>
  <p></p>
  <p></p>
  <p></p>
</div>
<style>
  body{
    background:#191919;
  }
  div {
    width: 150px;
    height: 150px;
    background: #4F77FF;
    margin:75px auto;
    border-radius:50%;
  }
  div:before, div:after{
    content:'';
    position:absolute;
  }
  div:before{
    width:210px;
    height:210px;
    border:10px solid #191919;
    border-radius:50%;
    box-sizing:border-box;
    top:50%;
    right:35px;
    transform:translateY(-50%);
    -webkit-box-reflect:left -90px;
  }
 div:after{
   width:10px;
   height:200px;
   background:#191919;
   left:195px;
 }
  p{
   position:absolute;
   width:200px;
   height:10px;
   background:#191919;  
    margin-top:30px
  }
  p:nth-of-type(1){
    top:115px;
  }
  p:nth-of-type(2){
    top:155px;
  }
</style>

```
