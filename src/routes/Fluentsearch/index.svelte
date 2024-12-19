<script>
	import Header from "$lib/header/Header.svelte";
	import * as Fluent from "fluent-svelte";
	import "fluent-svelte/theme.css";
	let dialogOpen = true; // Consider implementing dialog logic if needed
</script>

<h1 align="center">Fluent Search</h1>
<input type="text" placeholder="Search the web" form method="get" action="https://www.google.com/search" />

<div class="pad ctext">
	<button class="fluent-button" onclick="window.open('https://www.google.com/doodles', '_blank')">I'm Feeling Lucky</button>
</div>

<style>
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