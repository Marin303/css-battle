![](https://cssbattle.dev/targets/49@2x.png)

```HTML
<div>
<p></p>
  <p></p>
</div>
<span></span>
<style>
  body{
    background:#6592CF;
    margin:0;
    display:flex;
    justify-content:center;
  }
  div {
    margin-top:150px;
    width: 150px;
    height: 100px;
    border-radius:0 0 10px 10px;
    background: #243D83;
  }
  p{
    background:#EEB850;
  }
  p:first-child{
    margin:50px;
    width:50px;
    height:50px;
    border-radius:10px 10px 0 0;
  }
  p:last-child{
    margin-top:-155px;
    margin-left:25px;
    width:100px;
    height:10px;
    border-radius:10px;
  }
  span{
    z-index:-1;
    position:absolute;
    top:50px;
    width: 0;
	height: 0;
	border-left: 100px solid transparent;
	border-right: 100px solid transparent;
	border-bottom: 100px solid #243D83;
  }
</style>
```
