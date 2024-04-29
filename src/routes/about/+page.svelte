<svelte:head>
	<title>About</title>
	<meta name="description" content="About this iusebako... person." />
	<meta
		property="twitter:image"
		content="https://file.garden/ZgFjOBdyQ318TtyJ/1714097275391_49eff24a09ff38783624d3e59eba0636.webp"
	/>
</svelte:head>

<div class="text-column">
	<h1>Heya! I'm bako.</h1>

	<div class="centeritall">
		<h3>
			who's the newest hackclubber that's the average newbie webdev with very
			little experience in programming and backend? that's me!<br />
			<br />
			<h3>
				my name is iusebako (actual name Lucas R).<br /> texas resident, american,
				aroace, he/him/they/them, 13.
			</h3>
			<hr />
		</h3>

		<h3><b>Other Stuff you should *probably* know about me:</b></h3>

		<h3>
			I run a mod curation list over on <a href="https://modrinth.com/u/use"
				>my modrinth page</a
			>! It's under the name of <code>bako's tweaks and enhancements</code>.
		</h3>
	</div>
	<br />
	<div class="card-wrapper">
		<div class="pokemon-card">
			<h2>I'm a certified Phighting Addict!</h2>
			<img
				src="https://file.garden/ZgFjOBdyQ318TtyJ/1714097275391_49eff24a09ff38783624d3e59eba0636.webp"
				alt="Pokemon Image"
			/>
			<p>
				go play phighting roblox or I will recite the full phighting babies
				copypasta in the next hackclub huddle!
			</p>
		</div>
	</div>
	<h5>
		<hr />
		defo not a furry /srs
	</h5>
</div>

<style>
	.card-wrapper {
		width: 100%; /* or any other desired value */
		height: auto; /* or any other desired value */
		margin-right: 10px;
		float: left;
	}

	.text-column {
		display: flex;
		flex-wrap: wrap;
	}

	.pokemon-card {
		width: 200px;
		border: 2px solid black;
		border-radius: 10px;
		padding: 10px;
		text-align: center;
		margin: 10px;
		flex: 1 1 200px; /* Flex properties to control width and grow */
		float: left;
		margin-right: 5px;
	}

	.pokemon-card img {
		width: 100%;
		border-bottom: 1px solid black;
	}

	.pokemon-card p {
		margin-top: 10px;
	}
</style>
