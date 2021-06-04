<script lang="ts">
	import '../global.postcss';
	import ToggleTheme from '$lib/ToggleTheme.svelte';

</script>

<main>
	<div
		class="flex items-center justify-between w-full max-w-4xl mx-auto my-0 text-gray-900 sticky-nav md:my-8 bg-opacity-60 dark:text-gray-100"
	>
		<ToggleTheme />
	</div>
	<div class="p-8">
		<slot />
	</div>
</main>

<style lang="postcss">
</style>
