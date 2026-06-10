# #21. SitePoint Logo

Challenge: <https://cssbattle.dev/play/21>

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
  <div class="out">
    <div class="in l"></div>
    <div class="in s"></div>
  </div>
  <div class="out inverted">
    <div class="in l"></div>
    <div class="in s"></div>
  </div>
</div>
<style>
  body {
    background: #222;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .wrapper {
    transform: rotate(-45deg);
    width: 120px;
    height: 120px;
  }
  .out {
    width: 200px;
    height: 100px;
    position: absolute;
  }
  .out:not(.inverted) {
    left: 18.7;
    top: -5.8;
  }
  .inverted {
    transform: rotate(180deg);
```
