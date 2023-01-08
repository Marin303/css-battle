![](https://cssbattle.dev/targets/16.png)

```HTML
<div class="container">
  <div class="eye"></div>
</div>
<style>
  body{
    background:#0B2429;
    margin: 0;
  }
  .container {
    width: 200px;
    height: 200px;
    background: #998235;
    margin: 50px auto;
    border-radius: 50% 0;
    transform: rotate(45deg);
    position:relative;
  }
  .eye{
    width: 140px;
    height:140px;
    border: 20px solid #0B2429;
    background:#F3AC3C;
    border-radius: 50%;
    position:absolute;
    top:10px;
    left:50%;
    transform: translateX(-50%)
  }
  .eye:before {
    content: '';
    display: block;
    width: 50px;
    height: 50px;
    background: #0B2429;
    border-radius: 50%;
    position: absolute;
    top:50%;
    left:50%;
    transform: translate(-50%, -50%);
    
  }
</style>
```
