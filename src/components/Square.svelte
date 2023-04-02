<script lang="ts" type="module">
	import { gsap } from 'gsap';
	import { ScrollTrigger } from 'gsap/dist/ScrollTrigger';
	import { onMount } from 'svelte';

	gsap.registerPlugin(ScrollTrigger);

	onMount(() => {
		gsap.to('.square', {
			scrollTrigger: {
				trigger: '.square',
				// markers: true,
				scrub: 3,
				// pin: true,
				start: 'top center',
				toggleActions: 'restart pause reverse pause'
			},
			x: 500,
			rotation: 360,
			duration: 3
		});
	});
</script>

<div class="square" />

<style lang="scss">
	.square {
		width: 100px;
		height: 100px;
		background-color: #000;
	}
</style>
