<script>
	import Header from "$lib/header/Header.svelte";
	import * as Fluent from "fluent-svelte";
	import "fluent-svelte/theme.css";
	import { TextBox } from "fluent-svelte";
</script>

<h1 align="center">Fluent Search</h1>
<form on:submit={handleSubmit}>
	<!--<input type="search" bind:value={query} placeholder="Search the web" />-->
<TextBox type="search" placeholder="Search the web" style="text-align:center"/>
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
