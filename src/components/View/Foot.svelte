<script>
	import Tree from '../Tree.svelte';
</script>

<section>
	<Tree />

	<div class="container">
		<div>
			<img src="https://baconmockup.com/500/500" alt="" />
		</div>
		<div>
			<h3 class="mono">> dev</h3>
			<h3 class="mono">> art</h3>
			<h3 class="mono">> language learning ?</h3>
		</div>
	</div>
</section>

<style lang="scss">
	section {
		position: relative;
		overflow-x: hidden;
		background: skyblue;
	}

	.container {
		flex-wrap: wrap-reverse;
		align-items: center;

		div {
			flex: 1 1 0%;
			padding: 2rem;
			justify-content: center;
			align-items: center;
		}
	}
</style>
