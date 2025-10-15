<script>
	export let name;

function TestFunction(){
document.getElementById("demo").innerHTML = "Hello World";
}
</script>



<main>
	<h1>System {name} Tests!</h1>
	<p>For more information go to <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
</main>



<body>
  <!-- =================Practice from  svelte================================= -->
<p style="background-color:Tomato;"><i>This is Range.</i></p>

<p> Min is 0 and max is 180</p>
<div>
  <input type="range" id="volume" name="volume" min="0" max="180" />
  <label for="volume">Volume</label>
</div>


<p style="background-color:Tomato;"><i>This is Number.</i></p>
<p> Min is 0 and max is 180</p>
<input id="number" type="number" value="180" max="180" min="0"/>

<p> Min is 0 and max is 180</p>
<input id="number" type="number" value="180" max="180" min="0"/>

<p> Min is 0 and max is 180</p>
<input id="number" type="number" value="180" max="180" min="0"/>

<p> Min is 0 and max is 180</p>
<input id="number" type="number" value="180" max="180" min="0"/>

<p> Min is 0 and max is 180</p>
<input id="number" type="number" value="180" max="180" min="0"/>


<p id="demo"></p>
<p style="background-color:Tomato;"><i>This is Button.</i></p>
<button onclick="TestFunction()">Click Me<button>

  <!-- =================Practice from  svelte================================= -->
</body>



<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>