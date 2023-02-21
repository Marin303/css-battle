![](https://cssbattle.dev/targets/58@2x.png)

```HTML
<div></div>
<span></span>
<style>
  body{
    background:#191919;
  }
  div {
    width: 20px;
    height: 80px;
    background: #F9E492;
    margin:175px auto;
    transform:translateX(-5%);
    border-radius:0 0 10px 10px;
  }
  div:after, div:before{
    content:'';
    display:block;  
    border-radius:50%;
    position:absolute;     
  }
 
  div:before{
    width:40px;
    height:40px;
    margin:-30px 0 0 -10px; 
    background:#F9E492;
  } 
  div:after{
    background: linear-gradient(#191919 60%, #4F77FF 60%);
    width:100px;
    height:100px;
    margin:-110px 0 0 -40px; 
  }
  span{
    background:#4F77FF;
    width:140px;
    height:30px;
    border-radius: 6px 6px 30px 30px;
    position:absolute;
    top:85px;
    left:130px;
  }
  span:before{
    content:'';
    background:#4F77FF;
    width:100px;
    height:30px;
    border-radius: 6px 6px 30px 30px;
    position:absolute;
    top:-20px;
    left:20px;
    box-shadow: 0 0 0 10px #191919;
  }
  span:after{
    content:'';
    background:#4F77FF;
    width:30px;
    height:30px; 
    border-radius:50%;
    position:absolute;
    box-shadow: 0 0 0 10px #191919;
    top:-40px;
    left:55px;
  }
</style>

```
