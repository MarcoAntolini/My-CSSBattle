# #19. Cube

Challenge: <https://cssbattle.dev/play/19>

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
<div class="l"></div>
<div class="r"></div>
<div class="c"></div>
<style>
  body {
    background: #0B2429;
    margin: 0;
    display: flex;
    align-items: center;
    justify-content:center;
  }
  div {
    position: absolute;
    transform: rotate(45deg);
  }
  .c {
    background: #F3AC3C;
    top: 135px;
    width: 100px;
    height: 100px;
  }
  .l {
    background: #998235;
    width: 71px;
    height: 71px;
    left: 129;
    top: 79;
    transform: skewY(-45deg);
  }
  .r {
    background: #1A4341;
    width: 71px;
    height: 71px;
    right: 129;
```
