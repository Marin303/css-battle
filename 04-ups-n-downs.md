![](https://cssbattle.dev/targets/4.png)

```HTML
<div class="down-left"></div>
<div class="up"></div>
<div class="down-right"></div>

<style>
  body {
    margin: 0;
    background: #62306D;
  }
  div {
    width: 100px;
    height: 100px;
    background: #F7EC7D;
    border-top-left-radius: 50%;
    border-top-right-radius: 50%;
  }
  .down-left {
    transform: rotate(180deg);
    position: absolute;
    margin: 100px 0 0 50px;
  }
  .up{
    margin: 50 0 0 150px;
  }
  .down-right{
    transform: rotate(180deg);
    margin: 0 0 0 250px; 
  }
</style>


```
