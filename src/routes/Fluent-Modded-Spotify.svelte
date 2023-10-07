
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
  

<p align="center">Spotify, but with a hint of Fluent Design</p>
  
<div class="pad ctext">
<p align="center">
<a href="https://github.com/pronoy2108/Fluent-Modded-Spotify/releases/tag/v2.5">
    <img src="https://img.shields.io/github/v/release/pronoy2108/Fluent-Modded-Spotify?label=version"></a>

<Fluent.Button variant="accent" href="https://t.me/fms_app" target="_blank" rel="noopener noreferrer"><style>.button.style-accent.svelte-1ulhukx {
    background-color: hsl(140deg 70.59% 44.77%);
}</style><img align="left" alt="Telegram Channel (Updates)" width="21px" src="https://files.catbox.moe/sc0rt9.png">Telegram Channel (Updates)</Fluent.Button>
<img src="https://img.shields.io/github/downloads/pronoy2108/Fluent-Modded-Spotify/total">


</p>
<hr/>
</div>

<div class="pad ctext">
	<Fluent.Expander>Installation
	<svelte:fragment slot="content">
		<h2 id="installation">Installation</h2>

		<h4 id="windows">Windows:</h4>
		
		<Fluent.TextBlock>

		<ul>
			
		<li>Download the two files from Releases</li>
		
		<li>Copy them to a folder in an easily accessible location like Desktop</li>
		
		<li>Install <code>scoop</code> using <code>iwr -useb get.scoop.sh | iex</code></li>
		
		<li>After scoop is installed, type <code>Set-ExecutionPolicy unrestricted</code> in Powershell with elevated privileges</li>
		
		<li>Run Spotify.exe as admin (it's an sfx archive and requires admin to extract the files)</li>
		
		<li>Run <code>autorunscript.ps1</code> to install all dependencies</li>
		
		<li>Extract it to the same location</li>
		
		<li>Run <code>Fluent Spotify.exe</code></li>
		
		<li>Install it however you want, for all users/for the current user only</li>
		
		<li>After installing, go to the <code>Spotify</code> folder you just extracted and run <code>Spotify.exe</code></li>
		
		<li>You should have Fluent Design in the Spotify app now!</li>
		
		</ul>
		
		<h4 id="linux">Linux:</h4>
		
		<ul>
		<li>Download the two files from Releases</li>
		
		<li>Run <code>autorunscript.sh</code> to install all dependencies.</li>
		</ul>
		
		<h4 id="archlinuxanditsderivatives">Arch Linux and its Derivatives</h4>
		
		<p>Follow the same process for Linux above, except the install scripts can be downloaded from <a href="https://github.com/windowz414/FMS-Arch">here</a></p>
		
		<todo content="[windowz414]: Finish fullinstall_arch.sh (A script to unify FMS-Arch) and put its utilization instead." />
		
		<p>Note: <code>autorunscript.ps1</code>/<code>autorunscript.sh</code> is a file which automatically installs the dependencies for this app (needs admin priviledges to work)</p>
</Fluent.TextBlock>
</svelte:fragment>
</Fluent.Expander>
</div>
<hr />

<div class="pad ctext">
	<Fluent.Expander>Credits
	<svelte:fragment slot="content">

<ul>
			<Fluent.TextBlock>
			<li><a href="https://github.com/nimsandu/spicetify-bloom">Spicetify-bloom -</a><li><a href="https://github.com/khanhas/spicetify-cli">Spicetify</a> theme inspired by Windows 11 UI and Microsoft's Fluent Design</li>
		</Fluent.TextBlock>
		</ul>
<ul>
			<Fluent.TextBlock>

<li>Icon: Made by <a href="https://twitter.com/Qirkl">Qirkl</a></li>


			</Fluent.TextBlock>

<ul>
			<Fluent.TextBlock>

<li>Installation steps for Windows: <a href="https://github.com/donut2008">donut2008</a></li>

</ul>
			</Fluent.TextBlock>

		<ul>
			<Fluent.TextBlock>
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
<center>
	<article class="markdown-body">
		<img alt="App, Home Page (Dark Mode)" src="https://github.com/williamckha/spicetify-fluent/blob/master/screenshots/dark-1.png?raw=true">
		<img alt="App, Search Page (Dark Mode)" src="https://github.com/williamckha/spicetify-fluent/blob/master/screenshots/dark-2.png?raw=true">
		</article>
</center>
</Fluent.TextBlock>
</svelte:fragment>
</Fluent.Expander>
</div>
