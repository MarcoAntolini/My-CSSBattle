# Battle #2 - Visibility

## #14 - Web Maker Logo

[Link to the problem](https://cssbattle.dev/play/14)

![result](./images/014_web-maker-logo.png)

```html
<div class="a inverted"></div>
<div class="b inverted"></div>
<div class="b"></div>
<div class="a"></div>
<style>
  body {
    background: #F2F2B6;
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  div {
    border-right: 75px solid transparent;
    border-left: 75px solid transparent;
    display: inline-block;
  }
  .a {
    border-bottom: calc(75px * 0.866 * 2) solid #FD4602;
    margin: 0 -160px;
  }
  .b {
    border-bottom: calc(75px * 0.866 * 2) solid #FF6D00;
    margin: 0 -10px;
  }
  .inverted {
    transform: rotatez(0.5turn);
  }
</style>
```
