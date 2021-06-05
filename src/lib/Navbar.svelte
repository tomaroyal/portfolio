<script lang="ts">
	import ToggleTheme from '$lib/ToggleTheme.svelte';

</script>

<div
	class="flex items-center justify-between w-full max-w-4xl mx-auto text-gray-900 sticky-nav md:my-8 bg-opacity-60 dark:text-gray-100"
>
	<ToggleTheme />
	<div class="space-x-4">
		<a href="/">Home</a>
		<a href="/about">About</a>
	</div>
</div>
