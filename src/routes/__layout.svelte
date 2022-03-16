<script context="module">
	export const headerHeight = 44;
	export const navHeight = 20;
</script>

<script lang="ts">
	import '$lib/app.css';
</script>

<section class="h-screen flex flex-col">
	<header class="bg-blue-800 h-{headerHeight}">header</header>
	<nav class="p-4 text-lg bg-yellow-800 h-{navHeight}">
		<a class="underline" href="/a">a</a>
		<a class="underline" href="/b">b</a>
		<a class="underline" href="/c">c</a>
		<a class="underline" href="/d">d</a>
		<a class="underline" href="/e">e</a>
	</nav>
	<main class="grow overflow-auto">
		<slot />
	</main>
</section>
