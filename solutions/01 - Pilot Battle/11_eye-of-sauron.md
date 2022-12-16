# Battle #1 - Pilot Battle

## #11 - Eye of Sauron

[Link to the problem](https://cssbattle.dev/play/11)

![result](./images/11_eye-of-sauron.png)

```html
<div class="circle"></div>
<div class="semi"></div>
<div class="semi inverted"></div>
<style>
  body {
    background: #191210;
    margin: 0;
  }
  div {
    position: absolute;
  }
  .circle {
    width: 50px;
    height: 50px;
    background: #84271C;
    border-radius: 50%;
    border: 25px solid #191210;
    outline: 20px solid #ECA03D;
    margin: 100px 150px;
  }
  .semi {
    width: 60px;
    height: 30px;
    border-radius: 0 0 80px 80px;
    border: 20px solid #ECA03D;
    border-top: 0;
    margin: 150px 50px;
  }
  .inverted {
    transform: rotate(180deg) translate(-200px, 50px);    
  }
</style>
```
