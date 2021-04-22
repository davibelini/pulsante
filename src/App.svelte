<script>
	import Header from "./components/Header.svelte"
</script>

<main>
	<Header></Header>
</main>

<style>
	:global(html) {
		box-sizing: border-box;
	}
	:global(*), :global(*):before, :global(*):after {
		box-sizing: inherit;
	}
	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>