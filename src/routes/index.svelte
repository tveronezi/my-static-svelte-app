<script context="module" lang="ts">
	export const prerender = true;
</script>

<script lang="ts">
	let count = 0;
</script>

<div class="grid place-content-center text-center bg-gray-700 h-full space-y-16">
	<span>index!</span>
	<button class="p-4 bg-black text-white text-2xl w-32 rounded-lg" on:click={() => count++}
		>{count}</button
	>
</div>
