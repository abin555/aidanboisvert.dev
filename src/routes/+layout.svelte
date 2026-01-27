<script lang="ts">
	import "./layout.css";

	import { page } from "$app/stores";

	let { children } = $props();
</script>

<svelte:head><title>Aidan Boisvert</title></svelte:head>
{@render children?.()}