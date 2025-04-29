<script lang="ts">
	import '../css/app.css';
	let { children } = $props();
</script>

<svelte:head>
	<title>Hi UI</title>
</svelte:head>

{@render children()}
