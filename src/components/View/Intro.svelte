<main>
	<div class="container">
		<div class="side">
			<h1>>~/Patato</h1>
			<p>Code, Design, Art</p>
		</div>

		<div class="side">
			<img src="https://baconmockup.com/300/300" alt="Bacon Mockup" />
		</div>
	</div>

	<!-- <Square /> -->
</main>

<style lang="scss">
	main {
		background-image: url('/pattern.svg');
		background-repeat: repeat;
		border-bottom: solid 2px #414141;
	}

	.container {
		gap: 5rem;
		flex-wrap: wrap-reverse;
	}

	.side {
		min-width: 21rem;
		flex: 1 1 0%;
		display: flex;
		flex-direction: column;
		justify-content: center;
	}
</style>
