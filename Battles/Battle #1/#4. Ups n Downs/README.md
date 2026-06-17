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
<div></div>
<div class="show up"></div>
<div></div>
<div class="show"></div>
<div></div>
<div class="show"></div>
<style>
  body{
    background: #62306D;
    margin: 50px;
    display: grid;
    grid-template-columns: repeat(3, 100px);
    grid-template-rows: repeat(2, 100px);
  }
  .show{
    background: #F7EC7D;
    border-radius: 0 0 50% 50%;
  }
  .up{
    border-radius: 50% 50% 0 0;
  }
</style>
```
