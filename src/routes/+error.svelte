<script>
	import { onMount } from 'svelte';

	let countdown = 3;

	onMount(() => {
		setTimeout(() => {
			if (typeof window !== 'undefined') {
				window.location.href = '/';
			}
		}, 3000);

		const interval = setInterval(() => {
			countdown -= 1;
		}, 1000);
	});
</script>

<main>
	<h1>:/404</h1>
	<h2>Page not Found</h2>
	<br />
	<p>Going back to ./ in {countdown} seconds</p>
</main>
