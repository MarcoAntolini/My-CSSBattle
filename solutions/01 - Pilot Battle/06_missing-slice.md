# Battle #1 - Pilot Battle

## #6 - Missing Slice

[Link to the problem](https://cssbattle.dev/play/6)

![result](./images/06_missing-slice.png)

```html
<div class="a"></div>
<div class="b"></div>
<div class="c"></div>
<style>
  body {
    background: #E3516E;
    display: grid;
    grid-template-columns: repeat(2, 100px);
    grid-template-rows: repeat(2, 100px);
    margin: 50px 100px;
  }
  div {
    width: 100px;
    height: 100px;
  }
  .a {
    background: #51B5A9;
    border-radius: 100% 0 0 0;
  }
  .b {
    background: #FADE8B;
    border-radius: 0 100% 0 0;
  }
  .c {
    background: #F7F3D7;
    border-radius: 0 0 0 100%;
  }
</style>
```
