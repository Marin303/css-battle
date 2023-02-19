![](https://cssbattle.dev/targets/56@2x.png)

```HTML
<div>
  <span></span>
</div>
<figure>
  <p></p>
  <p></p>
  <p></p>
</figure>
<style>
body{
 background:#191919;
}  
  figure {
    z-index:-1;
    width: 80px;
    height: 40px;
    background: #4F77FF;
    position:absolute;
    top:160px;
    left:120px;
    border-radius:0 0 20px 20px;
     display:flex;
    
  }
  div {
    width: 120px;
    height: 100px;
    background: #4F77FF;
    position:absolute;
    top:85px;
    left:140px;
    border-radius:60px 60px 10px 10px;
  }
  :before, :after{
    content:'';
    width:40px;
    height:40px;
    border-radius:50%;
  }
  div:before{
    background:#191919;
    position:absolute;
    top:53px;
    left:15px;
  }
   div:after{
    background:#191919;
    position:absolute;
    left:65px;
    top:53px;
  }
  p{
 margin:30px 3px;
    width: 20px;
    height: 10px;
    background:red;
    border-radius:20px 20px 0 0;
    background:#191919;
  }
   span{
     z-index:1;
     position:absolute;
     top:90px;
     left:50px;
    width: 20px;
    height: 20px;
    background:red;
    border-radius:50px;
    background:#191919;
  }
</style>
```
