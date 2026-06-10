# #25. Blossom

Challenge: <https://cssbattle.dev/play/25>

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
<div class="g t l"></div>
<div class="y t r"></div>
<div class="y b l"></div>
<div class="g b r"></div>
<style>
  body {
    background: #998235;
  }
  div {
    position: absolute;
  }
  .g {
    width: 80px;
    height: 100px;
    background: #1A4341;
  }
  .y {
    width: 80px;
    height: 60px;
    background: #F3AC3C;
  }
  .t {
    top: 60;
  }
  .b {
    bottom: 60;
  }
  .l {
    left: 110;
    border-radius: 0 50px;
  }
  .r {
    right: 110;
    border-radius: 50px 0;
  }
</style>
```
