<script>
	import Header from "$lib/header/Header.svelte";
	import * as Fluent from "fluent-svelte";
	import "fluent-svelte/theme.css";
	let dialogOpen = false;
</script>
<h1 class="ctext"><p><a href="https://pronoy2108.github.io/pronoy2108"><img src="https://raw.githubusercontent.com/pronoy2108/pronoy2108/gh-pages/iceland_improved.png" alt="Header"></a></p></h1>
<div class="pad ctext">
	<Fluent.TextBlock>Welcome to pronoy2108's website!</Fluent.TextBlock>
</div>
<div class="pad ctext">
	<Fluent.Button variant="accent" href="https://github.com/pronoy2108" target="_blank" rel="noopener noreferrer"><img align="left" alt="GitHub" width="21px" src="https://raw.githubusercontent.com/pronoy2108/pronoy2108/7d94d746fd9b6638308501942f83535b3d0e4334/github.svg">GitHub</Fluent.Button>
&nbsp;
<Fluent.Button variant="accent" href="https://t.me/pronoy2108" target="_blank" rel="noopener noreferrer"><img align="left" alt="Telegram" width="21px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/82/Telegram_logo.svg/768px-Telegram_logo.svg.png">Telegram</Fluent.Button>
	<Fluent.Button variant="accent" href="https://gitlab.com/pronoy2108" target="_blank" rel="noopener noreferrer"><img align="left" alt="GitLab" width="21px" src="https://raw.githubusercontent.com/pronoy2108/pronoy2108/7d94d746fd9b6638308501942f83535b3d0e4334/gitlab.svg">GitHub</Fluent.Button>
	&nbsp;
	<Fluent.Button variant="accent" href="https://www.youtube.com/channel/UC2fvHRsz9lwtnRyFHEdR5wA" target="_blank" rel="noopener noreferrer"><img align="left" alt="YouTube" width="21px" src="https://raw.githubusercontent.com/pronoy2108/pronoy2108/7d94d746fd9b6638308501942f83535b3d0e4334/youtube.svg">GitHub</Fluent.Button>
	&nbsp;
<Fluent.Button variant="accent" on:click={()=>{dialogOpen=true}}><img align="left" alt="Discord" width="21px" src="https://raw.githubusercontent.com/anuraghazra/anuraghazra/master/assets/discord-round.svg">Discord</Fluent.Button>
	<Fluent.ContentDialog bind:open={dialogOpen} title="Opening profiles through URLs aren't implemented into Discord for now.">
	<div style="display: flex; flex-direction: column; gap: 3px; margin: 0;">
		<Fluent.TextBlock>You'll need to send a friend request on Discord (4sapCode#9284) to pm me.</Fluent.TextBlock>
	</div>
	<svelte:fragment slot="footer">
		<Fluent.Button variant="accent" on:click={() => { dialogOpen = false; }}>OK</Fluent.Button>
	</svelte:fragment>
	
&nbsp;
</Fluent.ContentDialog>
</div>
<div class="pad">
	<Fluent.Expander>About me
	<svelte:fragment slot="content">
<h1 id="heythereimgsrchttpsrawgithubusercontentcommartinheinzmartinheinzmasterwavegifwidth30px">Hey there! <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="30px"></h1>
		<Fluent.TextBlock>I'm Pronoy, a power user, open-source enthusiast, student developer, who is passionate about computer science.</Fluent.TextBlock>
		<p></p>
		<Fluent.TextBlock>You can find me here:
			<ul>
				<li>Discord - 4sapCode#9284</li> 
				<li>Telegram - @pronoy2108</li> 
				<li>GitHub - pronoy2108</li>
			</ul>
		</Fluent.TextBlock>
	</svelte:fragment>
</Fluent.Expander>
	<Fluent.Expander>GitHub projects
		<svelte:fragment slot="content">
			<ul>
				<li><Fluent.Button variant="hyperlink" href="https://pronoy2108.github.io/Superfolders" target="_blank" rel="noopener noreferrer">Superfolders</Fluent.Button></li>
				<li><Fluent.Button variant="hyperlink" href="https://github.com/pronoy2108/Fluent-Modded-Spotify" target="_blank" rel="noopener noreferrer">Fluent-Modded-Spotify</Fluent.Button></li>
				& many more cool projects
			</ul>
		</svelte:fragment>
	</Fluent.Expander>
	<Fluent.Expander>My GitHub Stats
		<svelte:fragment slot="content">
			<ul><p></p><p>
<a href="https://github.com/pronoy2108/pronoy2108">
<img src="https://github-readme-stats.vercel.app/api?username=pronoy2108&amp;show_icons=true&amp;theme=tokyonight">
</a>
</p><p></p> <p>
<img src="https://github-readme-streak-stats.herokuapp.com?user=pronoy2108&amp;theme=tokyonight">
</p>    <p><img src="https://metrics.lecoq.io/pronoy2108?template=classic&amp;isocalendar=1&amp;languages=1&amp;introduction=1&amp;habits=1&amp;stars=1&amp;topics=1&amp;reactions=1&amp;people=1&amp;gists=1&amp;followup=1&amp;lines=1&amp;traffic=1&amp;stargazers=1&amp;projects=1&amp;activity=1&amp;achievements=1&amp;discussions=1&amp;support=1&amp;notable=1&amp;repositories=1&amp;skyline=1&amp;pagespeed=1&amp;music=1&amp;tweets=1&amp;anilist=1&amp;stackoverflow=1&amp;posts=1&amp;rss=1&amp;wakatime=1&amp;stock=1&amp;nightscout=1&amp;screenshot=1&amp;repositories=100&amp;repositories.batch=100&amp;repositories.forks=false&amp;repositories.affiliations=owner&amp;isocalendar.duration=half-year&amp;languages.limit=8&amp;languages.sections=most-used&amp;languages.colors=github&amp;languages.threshold=0%25&amp;languages.indepth=false&amp;languages.categories=markup%2C%20programming&amp;languages.recent.categories=markup%2C%20programming&amp;languages.recent.load=300&amp;languages.recent.days=14&amp;introduction.title=true&amp;habits.from=200&amp;habits.days=14&amp;habits.facts=true&amp;habits.charts=false&amp;habits.trim=false&amp;stars.limit=4&amp;topics.mode=starred&amp;topics.sort=stars&amp;topics.limit=15&amp;reactions.limit=200&amp;reactions.limit.issues=100&amp;reactions.days=0&amp;reactions.display=absolute&amp;reactions.ignored=github-actions%5Bbot%5D%2C%20dependabot%5Bbot%5D%2C%20dependabot-preview%5Bbot%5D&amp;people.limit=24&amp;people.size=28&amp;people.types=followers%2C%20following&amp;people.identicons=false&amp;people.shuffle=false&amp;followup.sections=repositories&amp;projects.limit=4&amp;projects.descriptions=false&amp;activity.limit=5&amp;activity.load=300&amp;activity.days=14&amp;activity.filter=all&amp;activity.visibility=all&amp;activity.timestamps=false&amp;achievements.threshold=C&amp;achievements.secrets=true&amp;achievements.display=detailed&amp;achievements.limit=0&amp;notable.repositories=false&amp;skyline.year=current-year&amp;skyline.frames=60&amp;skyline.quality=0.5&amp;skyline.compatibility=false&amp;pagespeed.url=.user.website&amp;pagespeed.detailed=false&amp;pagespeed.screenshot=false&amp;music.limit=4&amp;music.played.at=false&amp;music.user=.user.login&amp;tweets.attachments=false&amp;tweets.limit=2&amp;tweets.user=.user.twitter&amp;anilist.medias=anime%2C%20manga&amp;anilist.sections=favorites&amp;anilist.limit=2&amp;anilist.limit.characters=22&amp;anilist.shuffle=true&amp;anilist.user=.user.login&amp;stackoverflow.user=0&amp;stackoverflow.sections=answers-top%2C%20questions-recent&amp;stackoverflow.limit=2&amp;stackoverflow.lines=4&amp;stackoverflow.lines.snippet=2&amp;posts.descriptions=false&amp;posts.covers=false&amp;posts.limit=4&amp;posts.user=.user.login&amp;rss.limit=4&amp;wakatime.days=7&amp;wakatime.sections=time%2C%20projects%2C%20projects-graphs%2C%20languages%2C%20languages-graphs%2C%20editors%2C%20os&amp;wakatime.limit=5&amp;wakatime.url=https%3A%2F%2Fwakatime.com&amp;wakatime.user=current&amp;stock.duration=1d&amp;stock.interval=5m&amp;screenshot.title=Screenshot&amp;screenshot.selector=body&amp;screenshot.background=true&amp;nightscout.url=https%3A%2F%2Fexample.herokuapp.com&amp;nightscout.datapoints=12&amp;nightscout.lowalert=80&amp;nightscout.highalert=180&amp;nightscout.urgentlowalert=50&amp;nightscout.urgenthighalert=250&amp;config.timezone=UTC" alt=""></p></ul>
		</svelte:fragment>
	</Fluent.Expander>
	<Fluent.Expander>Credits
		<svelte:fragment slot="content">
			<ul>
				<li><Fluent.Button variant="hyperlink" href="https://github.com/Tropix126" target="_blank" rel="noopener noreferrer">Tropix126</Fluent.Button></li>
				<li><Fluent.Button variant="hyperlink" href="https://github.com/TheOnlyTails" target="_blank" rel="noopener noreferrer">TheOnlyTails</Fluent.Button></li>
			</ul>
			<p></p>
			Thanks for porting Microsoft's Fluent UI to Svelte!
		</svelte:fragment>
	</Fluent.Expander>
</div>
<p></p>

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
