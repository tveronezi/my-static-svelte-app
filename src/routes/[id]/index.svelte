<script lang="ts">
	import { page } from '$app/stores';
</script>

<div class="grid place-content-center bg-gray-300 h-full">
	<span>page {$page.params.id}</span>
	<a href="/">home</a>
</div>
