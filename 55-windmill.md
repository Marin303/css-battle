![](https://cssbattle.dev/targets/55@2x.png)

```HTML
<div></div>
<span></span>
<style>
body{
  background:#191919;
}  
  div {
    width: 50px;
    height: 100px;
    background: #4F77FF;
    border-radius:0 50px 50px 0;
    position:absolute;
    top:50px;
    left:200px;
  }
  div:after{
    content:'';
    width: 50px;
    height: 100px;
    background: #4F77FF;
    border-radius:0 50px 50px 0;
    transform:rotate(180deg);
    position:absolute;
    top:100px;
    left:-50px;
  }
   span {
    width: 50px;
    height: 100px;
    background: #F9E492;
    border-radius:0 50px 50px 0;
     transform:rotate(90deg);
    position:absolute;
    top:125px;
    right:125px
  }
  span:after{
    content:'';
    width: 50px;
    height: 100px;
    background: #F9E492;
    border-radius:0 50px 50px 0;
    transform:rotate(180deg);
    position:absolute;
    top:100px;
    left:-50px;
  }
</style>

```
