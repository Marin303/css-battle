![](https://cssbattle.dev/targets/34@2x.png)
```HTML
<div></div>
<style>
  body{
    background: #007065;
    position:relative;
  }
  div {
    border-left: 130px solid transparent;
    border-right: 130px solid transparent;
    border-bottom: 90px solid #00A79D;
position: absolute;
    bottom: 42px;
    left: 60px;
  }
  div:before {
    display:block;
    content:"";
    border-left: 130px solid transparent;
    border-right: 130px solid transparent;
    border-bottom: 100px solid #F5C181;
position: absolute;
    top:-60px;
    left: -135px;
  }
  div:after {
    display:block;
    content:"";
    border-left: 130px solid transparent;
    border-right: 130px solid transparent;
    border-bottom: 100px solid #FFEECF;
position: absolute;
    bottom: 10px;
    left: -135px
  }
</style>

```
