# Target 4: Ups n Downs

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
<div class="wrapper">
  <div class="inner hide"></div>
  <div class="inner show up"></div>
  <div class="inner hide"></div>
  <div class="inner show down"></div>
  <div class="inner hide"></div>
  <div class="inner show down"></div>
</div>
<style>
  body {
    background: #62306D;
  }
  .wrapper {
    width: 300px;
    height: 200px;
    display: grid;
    grid-template-columns: repeat(3, 100px);
    grid-template-rows: repeat(2, 100px);
    margin: 50px auto;
  }
  .inner  {
    width: 100px;
    height: 100px;
  }
  .show {
    background: #F7EC7D;
  }
  .hide {
    background: #62306D;
```

## Submission Data

- Challenge: Target 4: Ups n Downs
- Score: 600.52
- Match: 100%
- Submitted at: 2026-05-15T02:47:46.774Z
