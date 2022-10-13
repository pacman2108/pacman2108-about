<script>
	import Header from "$lib/header/Header.svelte";
	import * as Fluent from "fluent-svelte";
	import "fluent-svelte/theme.css";
	let dialogOpen = true;
</script>

<h1 align="center"><p>Fluent Search</p></h1>
<TextBlock type="search" placeholder="Search the web" form method="get" action="https://www.google.com/search"></TextBlock>
<div class="pad ctext">
<Fluent.Button variant="standard" href="https://www.google.com/doodles" target="_blank" rel="noopener noreferrer">I'm Feeling Lucky</Fluent.Button>
</div>


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

