<script lang="ts">
	import '$lib/app.css';
	const links = ['a', 'b', 'c', 'd', 'e']
</script>

<section class="h-screen flex flex-col">
	<header class="bg-blue-800 h-44">header</header>
	<nav class="p-4 text-lg bg-yellow-800 h-36 space-x-4">
		{#each links as link}
			<a class="underline" href="/{link}">{link}</a>
		{/each}
	</nav>
	<main class="grow overflow-auto">
		<slot />
	</main>
</section>
