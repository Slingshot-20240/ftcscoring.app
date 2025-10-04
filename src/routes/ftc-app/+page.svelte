<script>
	import { onMount } from 'svelte';

	onMount(() => {
		window.location.href = 'https://theftc.app';
	});
</script>

<svelte:head>
	<title>Redirecting...</title>
	<link rel="canonical" href="https://theftc.app" />
</svelte:head>

<p>Redirecting to the FTC App...</p>
<p>presented by 20240 Slingshot</p>
<p>
	Not working? <a
		href="https://theftc.app"
		rel="noopener noreferrer">Click here</a
	>.
</p>

<style>
	p {
		font-family:
			system-ui,
			-apple-system,
			BlinkMacSystemFont,
			'Segoe UI',
			Roboto,
			Oxygen,
			Ubuntu,
			Cantarell,
			'Open Sans',
			'Helvetica Neue',
			sans-serif;
	}
</style>
