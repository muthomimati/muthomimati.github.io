<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
	 <title> muthomimati | political scientist and student of IR </title>
</svelte:head>

{@render children()}

