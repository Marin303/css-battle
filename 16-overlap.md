![](https://cssbattle.dev/targets/15.png)
```HTML
<div></div>
<div></div>
<style>
  body{
    margin: 0;
    background: #09042A;
    position:relative;
  }
  div {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    background: #7B3F61;
    position:absolute;
    top:80px;
    left:20%;
    transform:translate(0%, -5%)
  }
  div:nth-of-type(2) {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    background: #E78481;
    position:absolute;
    top:80px;
    left:45%;
    overflow:hidden;
  }
  div:nth-of-type(2):after {
    content: '';
    height: 100%;
    width: 100%;
    border-radius: 50%;
    background:#09042A;
    position:absolute;
    top:0;
    left: -100px;
  }
</style>
```
