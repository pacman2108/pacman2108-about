
<script> 
import Header from "$lib/header/Header.svelte";
import * as Fluent from "fluent-svelte";
import "fluent-svelte/theme.css";
</script>

<h2 align="center">
  Fluent-Modded-Spotify
</h2>
  
<center>
<img align="center" width="256" height="256" src="https://raw.githubusercontent.com/pronoy2108/Fluent-Modded-Spotify/main/spotify-icon.png">
  </center>
  
  <p align="center">Icon made by <a href="https://t.me/Qirkl">Qirkl</a></p>
<p align="center">Spotify, but with a hint of Fluent Design</p>
  

<p align="center">
<a href="https://github.com/pronoy2108/Fluent-Modded-Spotify/releases/tag/v2.5">
    <img src="https://img.shields.io/github/v/release/pronoy2108/Fluent-Modded-Spotify?label=version"></a>

<img src="https://img.shields.io/github/downloads/pronoy2108/Fluent-Modded-Spotify/total">
</p>
<hr/>

<div class="pad ctext">
	<Fluent.Expander>About
	<svelte:fragment slot="content">

</Fluent.TextBlock>
</svelte:fragment>
</Fluent.Expander>
</div>
<hr />

<div class="pad ctext">
	<Fluent.Expander>Credits
	<svelte:fragment slot="content">
<h3><a href="https://github.com/williamckha/spicetify-fluent">williamckha/spicetify-fluent</a></h3>
		<ul><Fluent.TextBlock>
			<li><a href="https://github.com/khanhas/spicetify-cli">Spicetify</a> theme inspired by Windows 11 UI and Microsoft's Fluent Design</li>
		</Fluent.TextBlock>
		</ul>
	
		<ul><Fluent.TextBlock>
			<p><li>
				<a href="https://github.com/amd64fox/BlockTheSpot">BlockTheSpot</a>, for adblocking binaries/files (Warning ⚠: These wouldn't work on the UWP versions of this app)
			</li>
			</p>
           </Fluent.TextBlock>
		   </ul>
		</svelte:fragment>
</Fluent.Expander>
<hr />
</div>

<div class="pad ctext">
	<Fluent.Expander>Screenshots
	<svelte:fragment slot="content">
		<center>
<Fluent.TextBlock>
<table>
	
<tr>
	<td>
	<img src="https://github.com/williamckha/spicetify-fluent/blob/master/screenshots/dark-1.png?raw=true" alt="App, Home Page (Dark Mode)">
</td>
</tr>

<tr>
	<td>
	<img src="https://github.com/williamckha/spicetify-fluent/blob/master/screenshots/dark-2.png?raw=true" alt="App, Search Page (Dark Mode)">
</td>
</tr>
	

<tr>
	<td>
		<img src="https://github.com/williamckha/spicetify-fluent/blob/master/screenshots/light-1.png?raw=true" alt="App, Home Page (Light Mode)">
	</td>
</tr>

<tr>
	<td>
	<img src="https://github.com/williamckha/spicetify-fluent/blob/master/screenshots/light-2.png?raw=true" alt="App, Search Page (Light Mode)">
</td>
</tr>
</center>
</Fluent.TextBlock>
</svelte:fragment>
</Fluent.Expander>
</div>

