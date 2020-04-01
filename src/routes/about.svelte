<svelte:head>
	<title>About</title>
</svelte:head>

{#each new Array(200) as _, i}
<p id={`anchor-${i}`}>This paragraph has id <code>anchor-{i}</code>.</p>
{/each}
