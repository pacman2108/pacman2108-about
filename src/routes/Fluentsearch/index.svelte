<script>
import * as Fluent from "fluent-svelte";
import "fluent-svelte/theme.css";
import { Button, Checkbox, ToggleSwitch, RadioButton, TextBox, Slider, Expander, ContentDialog, Flyout, InfoBar, InfoBadge, ProgressRing, PersonPicture, IconButton, TextBlock, ListItem
, CalendarView } from "fluent-svelte";
</script>

<h1 align="center">Fluent Search</h1>
<form on:submit={handleSubmit}>
	<!--<input type="search" bind:value={query} placeholder="Search the web" />-->

	<div class="pad ctext">
	<TextBox type="search" placeholder="Search the web" style="text-align:center"/>
		<Fluent.Button variant="standard" type="submit">Search</Fluent.Button>
			<Fluent.Button variant="standard" href="https://www.google.com/doodles" target="_blank" rel="noopener noreferrer">I'm Feeling Lucky</Fluent.Button>
	</div>
</form>

<style>
	@import url("https://unpkg.com/fluent-svelte/theme.css");
</style>
