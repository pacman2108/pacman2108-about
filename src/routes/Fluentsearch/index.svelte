<script>
	import Header from "$lib/header/Header.svelte";
	import * as Fluent from "fluent-svelte";
	import "fluent-svelte/theme.css";
	let query = '';
	
	function handleSubmit(event) {
		event.preventDefault();
		const searchUrl = `https://www.google.com/search?q=${encodeURIComponent(query)}`;
		window.open(searchUrl, '_blank');
	}
</script>

<h1 align="center">Fluent Search</h1>
<form on:submit={handleSubmit}>
	<Fluent.TextBlock type="search" bind:value={query} placeholder="Search the web"></Fluent.TextBlock>
	<div class="pad ctext">
		<Fluent.Button variant="standard" type="submit">Search</Fluent.Button>
	</div>
</form>

<style>
	@import url("https://unpkg.com/fluent-svelte/theme.css");
	@media(prefers-color-scheme: light){
		:root{
			font-size: 16px;
			text-align: left;
			color: black;
		}
	}
	@media(prefers-color-scheme: dark){
		:root{
			font-size: 16px;
			text-align: left;
			color: white;
		}
	}
	.pad {
		padding: 8px;
	}
	.ctext {
		text-align: center;
	}
	h1 {
		font-size: 40px;
	}
</style>
