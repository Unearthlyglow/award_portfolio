<script>
	import '@picocss/pico';
	import Footer from '$lib/Footer.svelte';
</script>

<div>
<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<Footer />

</div>

<style lang="scss">
	@import '$lib/styles/global.scss';


	h1 {
		color: $primary-red;

	}
</style>
