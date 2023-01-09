![](https://cssbattle.dev/targets/18@2x.png)
```HTML
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<style>
  body {
    margin:0;
    padding: 10px;
    background: #5C434C;
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-column-gap: 20px;
    grid-row-gap: 20px;
  }
  div {
    width: 80px;
    height: 80px;
    border-radius: 100px 0 0;
    background: #F09462;
  }
  div:nth-child(even){
    background: #F5D6B4;
  }
  div:nth-child(8){
    grid-column: 1/2;
    grid-row: 2;
  }
</style>
```
