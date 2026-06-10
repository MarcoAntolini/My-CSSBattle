# #24. Switches

Challenge: <https://cssbattle.dev/play/24>

## Result

<table>
	<tr>
		<th width="50%">User Submission</th>
		<th width="50%">Target</th>
	</tr>
	<tr>
		<td width="50%" align="center">
			<img src="./user.png" alt="User Submission" width="100%">
		</td>
		<td width="50%" align="center">
			<img src="./target.png" alt="Target" width="100%">
		</td>
	</tr>
</table>

## Code

```html
<div class="back l"></div>
<div class="circle l"></div>
<div class="back r"></div>
<div class="circle r"></div>
<style>
  body {
    background: #62306D;
  }
  div {
    position: absolute;
    width: 100px;
    height: 100px;
  }
  .circle {
    background: #F7EC7D;
    border-radius: 50%;
    top: 100;
  }
  .l {
    left: 80;
  }
  .r {
    right: 80;
  }
  .back {
    border-radius: 50% 50% 0 0;
  }
  .back.l {
    background: #AA445F;
    top: 50;
  }
  .back.r {
    background: #E38F66;
    transform: rotate(180deg);
```
