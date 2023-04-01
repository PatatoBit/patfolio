<nav>
	<a
		href="/
	"
	>
		<h3>C:/patato</h3>
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

		ul {
			list-style-type: none;
			display: flex;
			gap: 2em;

			li {
				font-size: 1.2em;
			}

			a {
				text-decoration: none;
				color: #000;
				border: solid 3px #414141;
				background-color: #eeeeee;
				padding: 0.5em 1em 0.5em 1em;
				border-radius: 0.25rem;
			}
		}
	}
</style>
