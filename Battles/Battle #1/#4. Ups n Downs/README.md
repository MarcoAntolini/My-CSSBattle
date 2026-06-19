# #4. Ups n Downs

Challenge: <https://cssbattle.dev/play/4>

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
<p><p s u><p><p s><p><p s>
<style>
body {
  background: #62306d;
  margin: 35 50;
  display: grid;
  grid: repeat(2, 100px) / repeat(3, 100px);
}
p {
  height: 100;
}
[s] {
  background: #f7ec7d;
  border-radius: 0 0 50% 50%;
}
[u] {
  border-radius: 50% 50% 0 0;
}
</style>
```
