# Battle #5 - Inline

## #29 - Suffocate

[Link to the problem](https://cssbattle.dev/play/29)

![result](./images/029_suffocate.png)

```html
<div class="a"></div>
<div class="b"></div>
<div class="c"></div>
<div class="d"></div>
<style>
  body {
    background: #1A4341;
    margin: 0;
    display: flex;
    flex-wrap: wrap;
  }
  div {
    width: 200px;
    height: 150px;
    background: #F3AC3C;
  }
  .a {
    border-radius: 0 0 100px 0;
  }
  .b {
    border-radius: 0 0 0 100px;
  }
  .c {
    border-radius: 0 100px 0 0;
  }
  .d {
    border-radius: 100px 0 0 0;
  }
</style>
```
