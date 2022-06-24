<script>
	import Library from "./library/Library.svelte"
	export let name;
</script>

<main>
	<Library />
</main>

<style>
	main {
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>