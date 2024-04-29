<script>
</script>

<svelte:head>
	<title>bako.hackclub.app</title>
	<meta
		name="description"
		content="who's the newest hackclubber that's the average newbie webdev with very little experience in programming and backend? that's me! iusebako. aroace, he/him/they/them, 13."
	/>
	<meta
		property="twitter:image"
		content="https://file.garden/ZgFjOBdyQ318TtyJ/1714097275391_49eff24a09ff38783624d3e59eba0636.webp"
	/>
</svelte:head>

<section>
	<h1>iusebako (Lucas R)'s stuff!</h1>
	<h3>This site is a WORK IN PROGRESS!!!!</h3>
	<hr />
	<h3>My Projects:</h3>
	<div class="card-wrapper">
		<div class="pokemon-card">
			<h2>Cover Art Downloader</h2>
			<img
				src="https://coverartarchive.org/img/big_logo.svg"
				alt="MusicBrainz CoverArtArchive Logo"
			/>
			<p>
				This is the MusicBrainz Coverart Archive Downloader! Download cover art
				with ease! Check it out at <a
					href="https://musicbrainz-id-to-coverart-iusebako.replit.app/"
					>This Link!</a
				>
			</p>
		</div>
		<div class="pokemon-card">
			<h2>BakoAUTH!</h2>
			<img
				src="https://file.garden/ZgFjOBdyQ318TtyJ/assets_hc/bauth.png"
				alt="BAuth Logo"
			/>
			<p>
				I've made a (pretty basic) authentication system for a web panel. It uses pocketbase for an registration and logins database! Live demo is over at <a href="https://pb.bako.hackclub.app">pb.bako.hackclub.app</a>. <a href="https://github.com/real-kwellercat/BakoAUTH">Github Here!</a>
			</p>
		</div>
	</div>
</section>

<style>
	.card-wrapper {
		width: 100%; /* or any other desired value */
		height: auto; /* or any other desired value */
		margin-right: 10px;
		float: left;
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
