
<style>
	h1, p {
		text-align: center;
		margin: 0 auto;
	}

	h1 {
		font-size: 2em;
		text-transform: uppercase;
		font-weight: 700;
		margin: 0 0 0.5em 0;
	}

	p {
		margin: 1em auto;
	}

	a {
		margin-top: 40px;
	}

	img{
		margin: 0 auto;
		display: block;
		border-radius: 3px;
	}

	div{
		margin-top: 60px;
		text-align: center;
	}

	@media (min-width: 480px) {
		h1 {
			font-size: 4em;
		}
	}
</style>

<svelte:head>
	<title>Job App</title>
</svelte:head>

<div>
	<!-- svelte-ignore a11y-missing-attribute -->
	<img src="https://picsum.photos/id/2/800/100?grayscale">
	<h1>Jobs!</h1>
	<p>Find your next project here</p>
	<a href="jobs" class="btn">View Jobs</a>
</div>