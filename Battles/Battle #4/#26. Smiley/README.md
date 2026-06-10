# #26. Smiley

Challenge: <https://cssbattle.dev/play/26>

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
<div class="a"></div>
<div class="b"></div>
<div class="c"></div>
<style>
  body {
    background: #6592CF;
  }
  div {
    width: 80px;
    height: 40px;
    background: #0000;
    position: absolute;
    border-radius: 80px 80px 0 0;
    border: 20px solid #060F55;
    border-bottom: 0;
  }
  .a {
    top: 40;
    right: 40;
  }
  .b {
    top: 40;
    left: 40;
  }
  .c {
    transform: rotate(180deg);
    bottom: 40;
    left: 140
  }
</style>
```
