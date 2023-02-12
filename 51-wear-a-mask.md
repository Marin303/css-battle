![](https://cssbattle.dev/targets/51@2x.png)

```HTML
<div>
 <span></span>
  <span></span>
</div>
<div></div>

<style>
  body{
    background:#293462;
    position:relative;
  }
  div:nth-of-type(1) {
    width: 150px;
    height: 100px;
    background: #FFF1C1;
    margin:100px auto;
    border-radius: 0 0 50px 50px
  }
  div:nth-of-type(2){
    width: 250px;
    height: 40px;
    background: #293462;
    position:absolute;
    top:0px;
    left:56px;
    border: 10px solid #FFF1C1;
    border-radius:30px;
    z-index:-1;
  }
   div:nth-of-type(1):after {
    width: 40px;
    height: 40px;
    content:'';
    display:block;
    background: #FE5F55;
    position:absolute;
    top:40px;
    right:137px;
    border-radius:50px
  }
   span {
    width: 40px;
    height: 10px;
    background: #FE5F55;
    position:absolute;
    top:20px;
     left:135px;
    border-radius: 50px
  }
  span:nth-of-type(1){
    top:40px;
  }
</style>

```
