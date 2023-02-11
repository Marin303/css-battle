![](https://cssbattle.dev/targets/50@2x.png)

```HTML
<span></span>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<p></p>
<style>
  body{
  background:#1A4341;
  margin:0;
    position:relative;
  }
  span{
    width: 100px;
    height: 100px;
    background: #998235;
    margin: 10px;
    border-radius:20px;
    position:absolute;
    bottom:0px;
    bottom:40px;
    left:35%
  }
  div:nth-of-type(1){
    width: 100px;
    height: 60px;
    background: #F3AC3C;
    position:absolute;
    left:150px;
    top:110px;
    border-radius:20px 20px 0 0
  }
  div:nth-of-type(1):after{
    content:'';
    display:block;
    width:50px;
    height:50px;
    background:#F3AC3C;
    border-radius:50%;
    position:absolute;
    top:30px;
    right:0px;
    z-index:1;
 }
  span:after{
    content:'';
    display:block;
    width:50px;
    height:50px;
    background:#998235;
    border-radius:50%;
    position:absolute;
    bottom:60px;
    z-index:1;
 }
   div:nth-of-type(2){
    width: 50px;
    height: 22px;
    background: #F3AC3C;
    position:relative;
    left:175px;
    top:90px;
    border-radius:10px 10px 0 0
  }
  div:nth-of-type(3){
    width: 20px;
    height: 25px;
    background: #F3AC3C;
    position:relative;
    left:190px;
    top:45px;
  }
  div:nth-of-type(4){
    width: 150px;
    height: 20px;
    background: #F3AC3C;
    position:relative;
    left:150px;
    top:3px;
    border-radius:10px
  }
  div:nth-of-type(5){
    width: 20px;
    height: 35px;
    background: #F3AC3C;
    position:relative;
    left:280px;
    top:-12px;
    border-radius:10px
  }
  p{
    width: 20px;
    height: 20px;
    background: #998235;
    position:absolute;
    left:280px;
    top:84px;
    border-radius:10px
  }
  p:after{
    content:'';
    display:block;
    width:20px;
    height:20px;
    background:#998235;
    border-radius:50%;
    position:absolute;
    bottom:-30px;
    z-index:1;
 }
</style>

```
