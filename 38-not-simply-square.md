![](https://cssbattle.dev/targets/38@2x.png)
```HTML
<div>
  <p></p>
</div>
<span>
  <p></p>
</span>
<style>
  body{
    margin:0;
    position:relative;
  }
  div, span {
    position: absolute;
    right:0;
    width: 50%;
    height: 100%;
    background: #293462;
  }
  span{
    background: #FFF1C1;
    left: 0;
  }
  p{
    background:#FE5F55; 
    position: absolute;
    
  }
  span > p{
    height: 34%;
    width: 75%;
    bottom: -6vh;
    box-shadow: 50px 0px #A64942;
    
  }
  div > p{
    top: -20px;
    width: 25vw;
    height: 51vh;
    box-shadow: 0px 51px #A64942;
  }
</style>

```
