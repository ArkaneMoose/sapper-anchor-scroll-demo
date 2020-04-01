<svelte:head>
	<title>Sapper Anchor Scroll Demo</title>
</svelte:head>

<h1>Sapper Anchor Scroll Demo</h1>

<p>First, go to the <a href="about">about tab</a> and observe the 200 paragraphs on that page, each with their own anchor.</p>

<p>Then, return to this page, and <a href="#bottom">click here to go to the bottom of the page.</a></p>

{#each new Array(100) as _, i}
<p>Filler text.</p>
{/each}

<p id="bottom">Welcome to the bottom of the page. Finally, <a href="about#anchor-100">click here to go to <code>anchor-100</code> on the about page.</a></p>
