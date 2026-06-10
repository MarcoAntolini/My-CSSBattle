# Daily Target — Jun 10, 2026

Challenge: <https://cssbattle.dev/play/UyIHaMHngnvBrD7ecqUs>

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
<div><div></div></div>
<div class="r"><div></div></div>
<div class="a"></div>
<style>
  body {
    background: #4C4C6B;
    display: flex;
    gap: 40px;
    margin: 50 40;
  }
  div {
    position: absolute;
    background: #4C4C6B;
  }
  div:has(> div) {
    width: 140px;
    height: 200px;
    background: #FAE29E;
    border-radius: 70px 70px 0 0;
    position: relative;
    div {
      width: 30px;
      height: 160px;
      left: 55;
    }
  }
  .r {
    rotate: 180deg;
  }
  .a {
    height: 30px;
    width: 400px;
    top: 135;
  }
</style>
```
