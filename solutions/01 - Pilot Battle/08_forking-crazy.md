# Battle #1 - Pilot Battle

## #8 - Forking Crazy

[Link to the problem](https://cssbattle.dev/play/8)

![result](./images/08_forking.crazy.png)

```html
<div class="bot"></div>
<div class="rect"></div>
<div class="wrapper">
  <div class="inner"></div>
  <div class="inner reverse"></div>
  <div class="inner"></div>
  <div class="inner reverse"></div>
  <div class="inner"></div>
  <div class="inner reverse"></div>
  <div class="inner"></div>
</div>
<style>
  body {
    background: #6592CF;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  div:not(.wrapper):not(.reverse) {
    background: #060F55;
  }
  div:not(.inner):not(.reverse) {
    position: absolute;
  }
  .wrapper {
    display: flex;
    bottom: 140px;
  }
  .inner {
    height: 110px;
    width: 20px;
    border-radius: 20px 20px 0 0;
  }
  .reverse {
    transform: scaleY(-1);
    background: #6592CF;
  }
  .bot {
    height: 100px;
    width: 140px;
    border-radius: 0 0 80px 80px;
    bottom: 50px;
  }
  .rect {
    height: 80px;
    width: 20px;
    bottom: 0;
  }
</style>
```
