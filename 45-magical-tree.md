![](https://cssbattle.dev/targets/45@2x.png)
```HTML
<div></div>
<p></p>
<style>
  body{
    background:#1A4341;
    margin:0;
  }
  div {
    border:30px solid #998235;
    width: 90px;
    height: 120px;
    border-top: none;
    margin-left:125px;
    position:relative;
    z-index:-1;
  }
 
  div:after{
    content:'';
    display:block;
    width:270px;
    height:30px;
    background:#998235;
    position:absolute;
bottom:-150px;
    left:-90px;
    z-index:-1;
  }
p {
    border:30px solid #F3AC3C;
    width: 210px;
    height: 200px;
    border-top: none;
    margin:-170px 65px;

    
  }
  p:before{
    content:'';
    display:block;
    width:30px;
    height:180%;
    background:#F3AC3C;
    margin:auto;
  }

</style>

```
