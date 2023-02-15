![](https://cssbattle.dev/targets/54.png)

```HTML
<div>
  <span></span>
  <span></span>
  <span></span>
  <span></span>
  <span></span>
</div>
<style>
body{
  background:#F9E492;
}  
  div {
    width: 100px;
    height: 55px;
    position:absolute;
    top:78px;
    left:50%;
    transform:translateX(-50%);
    display:flex;
    align-items:flex-end;
  }
 
  :before, :after{
    content: '';
    position:absolute;
    background:#191919;
    border-radius: 0 0 10px 10px;
  }
 div:before{
   width:100%;
   height:40px;
   bottom:-5px;
   transform:translateY(100%);
 }
   div:after{
   width:50px;
   height:45px;
   bottom:-45px;
   left:50%;
   transform:translate(-50%, 100%);
 }
   span{
    background:#191919;
    width:calc((100% - 20px)/4);
    border-radius:10px;
    margin-left:5px;
     height:100%;
  }
  span:nth-child(1){
    /*display:none;*/
    position:absolute;
    height:65px;
    transform:rotate(60deg);
    top:32px;
    left:2px;
    box-shadow:0 0 0 5px #F9E492;
  }
span:nth-child(2){
    height:45px
  }
  span:nth-child(4){
    height:45px
  }
  span:nth-child(5){
    height:35px
  }
</style>
```
