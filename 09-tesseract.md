![](https://cssbattle.dev/targets/9.png)

```HTML
  <div class="rectangle"></div>
  <div class="square"></div>
<style>
    body{
    background: #222730;
    }
  .rectangle{
    width: 100%;
    height: 150px;
    background: #4CAAB3;
    position:absolute;
    top: 50%;
    left:0;
    transform: translateY(-50%);
  } 
  .square {
    width: 150px;
    height: 150px;
    position: absolute;
    top:50%;
    left:50%;
    transform: translate(-50%, -50%) rotate(-45deg);
    background: #4CAAB3;  
    box-shadow: 0 0 0 50px #222730;
    }
  .square:after{
    display:block;
    content:'';
    width: 50px;
    height: 50px;
    position: absolute;
    top:50%;
    left:50%;
    transform: translate(-50%, -50%);
    border-radius: 50%;
    background: #393E46;  
  }
</style>

```
