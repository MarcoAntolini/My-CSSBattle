# Battle #1 - Pilot Battle

## #4 - Ups n Downs

[Link to the problem](https://cssbattle.dev/play/4)

![result](./images/04_ups-n-downs.png)

```html
<div class="wrapper">
  <div class="inner hide"></div>
  <div class="inner show up"></div>
  <div class="inner hide"></div>
  <div class="inner show down"></div>
  <div class="inner hide"></div>
  <div class="inner show down"></div>
</div>
<style>
  body {
    background: #62306D;
  }
  .wrapper {
    width: 300px;
    height: 200px;
    display: grid;
    grid-template-columns: repeat(3, 100px);
    grid-template-rows: repeat(2, 100px);
    margin: 50px auto;
  }
  .inner  {
    width: 100px;
    height: 100px;
  }
  .show {
    background: #F7EC7D;
  }
  .hide {
    background: #62306D;
  }
  .down {
    border-radius: 0 0 50% 50%;
  }
  .up {
    border-radius: 50% 50% 0 0;
  }
</style>
```
