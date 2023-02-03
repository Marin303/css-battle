![](https://cssbattle.dev/targets/42@2x.png)

```HTML
<div>
  <p></p>
</div>

<style>
  body{
    background:#293462;
    margin:0;
  }
  div {
    width: 100px;
    height: 200px;
    background: #FE5F55;
    position:absolute;
    bottom:50px;
    left:100px;
    border-radius: 100px 0 0 50px;
    overflow:hidden;
    -webkit-box-reflect: right;
  }
  div:before, div:after{
    content:'';
    display:block;
    border-radius:50%;
    background:#FFF1C1;
    position:absolute;
  }
  div:after{
    width:100px;
    height:100px;
    top:-50px;
  }
  div:before{
    width:60px;
    height:60px;
    top:90px;
    left:20px;
  }
    p{
    background:#FFF1C1;
    border-radius:;
    position:absolute;
    width:26px;
    height:10px;
    top:154px;
    right:-5px;
    border-radius:10px
    }
</style>

```
