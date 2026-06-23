# #15. Overlap

Challenge: <https://cssbattle.dev/play/15>

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
<div class="circle left"></div><div class="circle right"></div><div class="mid"></div>
<style>
body {
  background: #09042a;
  margin: 0;
}
div {
  position: absolute;
}
.circle {
  width: 150px;
  height: 150px;
  background: #7b3f61;
  border-radius: 50%;
}
.left {
  background: #7b3f61;
  margin: 75px;
}
.right {
  background: #e78481;
  margin: 75px 175px;
}
.mid {
  width: 80px;
  height: 80px;
  background: #09042a;
  border-radius: 100% 5%;
  transform: rotate(-45deg);
  margin: 110px 160px;
}
</style>
```
