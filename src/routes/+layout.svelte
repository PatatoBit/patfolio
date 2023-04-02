<script>
	import Nav from '../components/Nav.svelte';
	import '../styles/global.scss';
</script>

<svelte:head>
	<title>C:/patato</title>
	<meta name="description" content="Full-stack dev from Thailand" />

	<!-- Facebook Meta Tags -->
	<meta property="og:url" content="https://patato.vercel.app" />
	<meta property="og:type" content="website" />
	<meta property="og:title" content="C:/patato" />
	<meta property="og:description" content="Full-stack dev from Thailand" />
	<meta property="og:image" content="/banner.png" />

	<!-- Twitter Meta Tags -->
	<meta name="twitter:card" content="summary_large_image" />
	<meta property="twitter:domain" content="patato.vercel.app" />
	<meta property="twitter:url" content="https://patato.vercel.app" />
	<meta name="twitter:title" content="C:/patato" />
	<meta name="twitter:description" content="Full-stack dev from Thailand" />
	<meta name="twitter:image" content="/banner.png" />
</svelte:head>

<Nav />
<slot />
