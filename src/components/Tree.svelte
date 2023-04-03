<script lang="ts" type="module">
	import { gsap } from 'gsap';
	import { ScrollTrigger } from 'gsap/dist/ScrollTrigger';
	import { onMount } from 'svelte';

	gsap.registerPlugin(ScrollTrigger);

	onMount(() => {
		gsap.to('.clouds1', {
			scrollTrigger: {
				trigger: '.clouds1',
				// markers: true,
				scrub: 3,
				pin: true,
				start: 'top center',
				toggleActions: 'restart pause reverse pause'
			},
			x: '1300px',
			duration: 3
		});

		gsap.to('.clouds2', {
			scrollTrigger: {
				trigger: '.clouds2',
				// markers: true,
				scrub: 3,
				pin: true,
				start: 'top center',
				toggleActions: 'restart pause reverse pause'
			},
			x: '-1300px',
			duration: 3
		});
	});
</script>

<div class="clouds1 bush" />
<div class="clouds2 bush" />

<style lang="scss">
	.bush {
		position: absolute;
		width: 636px;
		height: 488px;
		top: 0;
		background-repeat: no-repeat;
		z-index: 100;
	}

	.clouds1 {
		background-image: url('../assets/clouds-1.png');
	}

	.clouds2 {
		background-image: url('../assets/clouds-2.png');
	}
</style>
