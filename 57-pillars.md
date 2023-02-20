![](https://cssbattle.dev/targets/57@2x.png)

```HTML
<div></div>
<span>
  <p></p>
  <p></p>
</span>
<span>
  <p></p>
  <p></p>
</span>
<style>
  body{
    background:#191919;
  }
  div:nth-of-type(1) {
    width: 110px;
    height: 110px;
    background: #4F77FF;
    position:absolute;
    top:95px;
    left:145px;
  }
   span:nth-of-type(1) {
    width: 60px;
    height: 60px;
    background: #191919;
    position:absolute;
    top:75px;
    left:125px;
     border-radius:50%;
     -webkit-box-reflect: below 30px;
  }
     p:nth-of-type(1) {
    width: 45px;
    height: 45px;
    background: #F9E492;
    position:absolute;
    top:-15px;
     border-radius:50%;
  }
  p:nth-of-type(2) {
    width: 30px;
    height: 30px;
    background: #4F77FF;
    position:absolute;
    top:-15px;
     border-radius:50%;
  }
  p:nth-of-type(3){
    left:50px;
  }
span:nth-of-type(2){
        width: 60px;
        height: 60px;
        background: #191919;
        position: absolute;
        top: 75px;
        left: 215px;
        border-radius: 50%;
  -webkit-box-reflect: below 30px;
    }
 
  span:nth-of-type(2) p:nth-of-type(1){
        position: absolute;
    left:15px ;
    top:-15px ;
  }
  span:nth-of-type(2) p:nth-of-type(2){
    position: absolute;
    top:-15px;
    left:30px;
  }
</style>

```
