# Battle #1 - Pilot Battle

## #10 - Cloaked Spirits

[Link to the problem](https://cssbattle.dev/play/10)

![result](./images/010_cloaked-spirits.png)

```html
<div class="wrapper r">
  <div></div>
  <div class="rect"></div>
  <div></div>
  <div class="rect"></div>
  <div class="rect"></div>
  <div class="rect"></div>
</div>
<div class="wrapper c">
  <div></div>
  <div class="circle inverted"></div>
  <div></div>
  <div class="circle"></div>
  <div></div>
  <div class="circle"></div>
</div>
<style>
  body {
    background: #62306D;
    margin: 0;
  }
  .wrapper {
    display: grid;
    position: absolute;
    grid-template-columns: repeat(3, 100px);
    grid-template-rows: repeat(2, 100px);
  }
  .r {
    margin: 100px 50px;
  }
  .c {
    margin: 50px;
  }
  .rect {
    background: #F7EC7D;
  }
  .circle {
    width: 60px;
    height: 60px;
    background: #E38F66;
    border-radius: 50%;
    border: 20px solid #AA445F;
  }
  .inverted {
    background: #AA445F !important;
    border-color: #E38F66 !important;
  }
</style>
```
