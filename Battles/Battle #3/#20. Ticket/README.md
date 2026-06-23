# #20. Ticket

Challenge: <https://cssbattle.dev/play/20>

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
<div class="y"></div><div class="o"></div>
<style>
body {
  background: #62306d;
  display: flex;
  align-items: center;
  justify-content: center;
}
div {
  height: 100px;
}
.y {
  width: 140px;
  background:
    radial-gradient(circle at 0 100%, transparent 23%, #f7ec7d 24%),
    radial-gradient(circle at 100% 100%, transparent 11%, #f7ec7d 12%),
    radial-gradient(circle at 100% 0, transparent 11%, #f7ec7d 12%),
    radial-gradient(circle at 0 0, transparent 23%, #f7ec7d 24%);
  background-position:
    bottom left,
    bottom right,
    top right,
    top left;
  background-size: 50% 50%;
  background-repeat: no-repeat;
}
.o {
  width: 60px;
  background:
    radial-gradient(circle at 0 100%, transparent 17%, #e38f66 18%),
    radial-gradient(circle at 100% 100%, transparent 34%, #e38f66 35%),
    radial-gradient(circle at 100% 0, transparent 34%, #e38f66 35%),
    radial-gradient(circle at 0 0, transparent 17%, #e38f66 18%);
  background-position:
    bottom left,
    bottom right,
    top right,
    top left;
  background-size: 50% 50%;
  background-repeat: no-repeat;
}
</style>
```
