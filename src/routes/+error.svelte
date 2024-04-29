<script>
	let button = { clicked: true };

	function toggle() {
		button.clicked = !button.clicked;
	}
</script>

<head>
	<title>How did YOU get here?</title>
	<meta
		description="uhmmmm this was an error. we're making a not here, huge failure."
	/>
</head>

<section>
	<h1>You found a wild 404!</h1>
	<button on:click={toggle()}>Catch!</button>
	{#if !button.clicked}
		<h3>
			The 404 ran away, but... you can go <a href="/">back to the home page!</a>
		</h3>
		<p class="hidden">note for people contributing: dont fix this issue because it's funny how it doesnt let you click the button!</p>
	{/if}
</section>


<style>
	.hidden {
		opacity: 0.35;
	}
</style>