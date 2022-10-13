<script lang="ts">
	import Header from '$lib/header/Header.svelte';
	import '../app.css';
	import * as Fluent from "fluent-svelte";
    </script>

<Header />

<main>
	<slot/>
</main>

<footer>
	<div class="pad">
        <div class="textalign">
            <img src="https://raw.githubusercontent.com/pronoy2108/pronoy2108.about/master/error.svg" alt="error">
        </div>
        <h1 class="ctext">Something went wrong! ☹️</h1>
    </div>
    <div class="pad">
		<div class="ctext">
        <Fluent.TextBlock>
		<ul>
	<li> Make sure the web address is correct </li>
	<li> <Fluent.Button variant="hyperlink" href="javascript:history.go(-1)">Go back to the previous page</Fluent.Button> </li>
	<li> <Fluent.Button variant="hyperlink" href="javascript:reload()">Refresh this page</Fluent.Button> </li>
	<li> This page is down or has bugs </li>
		<ul>
		</Fluent.TextBlock>
	</div>
    </div>
</footer>

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
	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		padding: 1rem;
		width: 100%;
		margin: 0 auto;
		box-sizing: border-box;
	}
	
	footer {
		display: flex;
		flex-direction: column;
		justify-content: stretch;
		align-items: stretch;
		padding: 40px;
	}
	.textalign {
		text-align: center;
	}
	@media (min-width: 480px) {
		footer {
			padding: 0px 40px 40px;
		}
	}
	h1 {
		font-size: 40px;
	}
    .ctext {
		text-align: center;
	}
</style>
