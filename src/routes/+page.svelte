<script>
	import Square from '../components/Square.svelte';
</script>

<main>
	<div class="container">
		<div class="side">
			<h1 class="typewriter">>~/Patato</h1>
			<p>Code, Design, Art</p>
		</div>

		<div class="side">
			<img src="https://baconmockup.com/300/300" alt="Bacon Mockup" />
		</div>
	</div>

	<!-- <Square /> -->
</main>

<section>
	<h2>...</h2>
</section>

<style lang="scss">
	.typewriter {
		overflow: hidden; /* Ensures the content is not revealed until the animation */
		border-right: 0.15em solid orange; /* The typwriter cursor */
		white-space: nowrap; /* Keeps the content on a single line */
		animation: typing 1s steps(8, end), blink-caret 0.6s step-end infinite;
	}

	/* The typing effect */
	@keyframes typing {
		from {
			width: 0;
		}
		to {
			width: 100%;
		}
	}

	/* The typewriter cursor effect */
	@keyframes blink-caret {
		from,
		to {
			border-color: transparent;
		}
		50% {
			border-color: orange;
		}
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
