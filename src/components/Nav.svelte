<nav class="bg-blur">
	<a
		href="/
	"
	>
		<h4>C:/patato</h4>
	</a>
	<ul>
		<li class="mono"><a href="/">./</a></li>
		<li class="mono"><a href="/about">./about</a></li>
		<li class="mono"><a href="/contact">./contacts</a></li>
	</ul>
</nav>

<style lang="scss">
	nav {
		position: fixed;
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
		gap: 2em;

		padding: 1rem;

		border: solid 2px #414141;
		border-top: 0;
		border-left: 0;
		padding: 0.5em 1em 0.5em 1em;

		a {
			text-decoration: none;
			color: black;
		}

		ul {
			/* backdrop-filter: blur(24px); */

			list-style-type: none;
			display: flex;
			gap: 2em;

			li {
				font-size: 1.2em;
			}

			a {
				text-decoration: none;
				color: #000;
			}
		}
	}
</style>
