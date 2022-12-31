![](https://cssbattle.dev/targets/11.png)
```HTML
<div></div>
<style>
  body{
    background:#191210;
    margin: 0;
  }
  div {
    width: 0;
    border: 25px solid #84271C;
    border-radius: 50%;
    margin: 125px 0 0 175px;
    box-shadow: 
      0 0 0 25px #191210,
    0 0 0 45px #ECA03D;
    position: relative;
  }
  div:before {
    content: '';
    position: absolute;
    width: 60px;
    height: 60px;
    border-top: 20px solid transparent;
    border-right: 20px solid transparent;
    border-bottom: 20px solid #ECA03D;
    border-left: 20px solid #ECA03D;
    border-radius: 50%;
    left: -150px;
    top: -50px;
    transform: rotate(-45deg)
  }
  div:after{
    content: '';
    position: absolute;
    width: 60px;
    height: 60px;
    border-top: 20px solid #ECA03D;
    border-right: 20px solid transparent;
    border-bottom: 20px solid 
      transparent;
    border-left: 20px solid #ECA03D;
    border-radius: 50%;
    left: 50px;
    top: -50px;
    transform: rotate(45deg)
  }
</style>
```
