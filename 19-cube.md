![](https://cssbattle.dev/targets/19@2x.png)
```HTML
<div class="cover"></div>
<div class="coverR"></div>
<div class="coverL"></div>
<style>
  body {
    background: #0B2429;
    margin: 0;
    display: flex;
    justify-content: center;
  }
  .cover {
    width: 100px;
    height: 100px;
    background: #F3AC3C;
    transform: rotate(45deg);
    margin: 135px auto;
    position:absolute;
  }
  .coverR {
    width: 70px;
    height: 70px;
    background: #1A4341;
    position:absolute;
    top: 80px;
    right: 130px;
    transform: skew(0deg, 45deg)
  }
   .coverL {
    width: 70px;
    height: 70px;
    background: #998235;
    position:absolute;
    top: 80px;
    left: 130px;
    transform: skew(0deg, -45deg)
  }
</style>
```
