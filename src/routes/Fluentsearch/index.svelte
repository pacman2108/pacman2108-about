<script>
	import Header from "$lib/header/Header.svelte";
	import * as Fluent from "fluent-svelte";
	import "fluent-svelte/theme.css";
	let dialogOpen = true;
	let query = '';
	
	function handleSubmit(event) {
		event.preventDefault();
		const searchUrl = `https://www.google.com/search?q=${encodeURIComponent(query)}`;
		window.open(searchUrl, '_blank');
	}
</script>

<h1 align="center">Fluent Search</h1>
<form on:submit={handleSubmit}>
	<input type="search" bind:value={query} placeholder="Search the web" />
	<div class="pad ctext">
		<Fluent.Button variant="standard" type="submit">Search</Fluent.Button>
	</div>
</form>
<div class="pad ctext">
	<Fluent.Button variant="standard" href="https://www.google.com/doodles" target="_blank" rel="noopener noreferrer">I'm Feeling Lucky</Fluent.Button>
</div>

<style>
	@import url("https://unpkg.com/fluent-svelte/theme.css");
</style>
