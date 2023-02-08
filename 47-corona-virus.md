![](https://cssbattle.dev/targets/47@2x.png)

```HTML
<div>
  <p></p>
  <p></p>
  <p></p>
</div>
<span></span>
<span></span>
<span></span>
<a></a>
<a></a>
<a></a>
<style>
  body{
    background:#1A4341;
    display:flex;
    justify-content: center;
  }
  span{   
    position:absolute;
    width:10px;
    height:60px;
    border-radius:10px;
    background:#F3AC3C;
  }
   span:nth-of-type(1){
    top:50px;

  }
    span:nth-of-type(2){
    top:85px;
    right:135px;
    transform:rotate(60deg);
    }
  span:nth-of-type(3){
    top:155px;
    left:255px;
    transform:rotate(-60deg);
  }
  a{   
    position:absolute;
    width:10px;
    height:40px;
    border-radius:10px;
    background:#F3AC3C;
  }
  
  a:nth-of-type(1){
    top:190px;

  }
    a:nth-of-type(2){
    top:100px;
    right:245px;
    transform:rotate(-60deg);
    }
  a:nth-of-type(3){
    top:160px;
    left:140px;
    transform:rotate(60deg);
  }
  div {
    width: 100px;
    height: 100px;
    background: #F3AC3C;
    border-radius:50%;
    margin: auto;
    position: relative;
  }
  p{
    position: absolute;
    background:#998235;
    border-radius:50%;
  }
  p:first-child{
    width: 30px;
    height: 30px;
    top:5px;
    right:50px;
  }
  p:nth-of-type(2){
    width: 20px;
    height: 20px;
    top:50px;
    right:40px;
  }
    p:nth-of-type(3){
    width: 10px;
    height: 10px;
    top:5px;
    left:70px;
    }
</style>

```
