![](https://cssbattle.dev/targets/7.png)

´´´HTML

<div></div>
<div></div>
<div></div>

<style>
  body {
    background: #0B2429;
    margin: 80px;
    position:relative;
  }
  div:first-child {
    width: 140px;
    height: 140px;
    background: #F3AC3C;
    border-top-left-radius: 70%;
    border-bottom-right-radius: 70%;
    position:absolute;
    right: 0;
  }
  div:nth-of-type(2) {
    width: 140px;
    height: 140px;
    background: #998235;
    border-top-left-radius: 70%;
    border-bottom-right-radius: 70%;
    position:absolute;
    right: 50px;
    z-index: -1;
  }
   div:last-of-type {
    width: 140px;
    height: 140px;
    background: #1A4341;
    border-top-left-radius: 70%;
    border-bottom-right-radius: 70%;
    position:absolute;
    right: 100px;
    z-index: -2;
  }
</style>

```
