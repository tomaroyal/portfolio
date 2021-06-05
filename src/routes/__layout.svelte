<script lang="ts">
	import '../global.postcss';
	import Footer from '$lib/Footer.svelte';
	import Navbar from '$lib/Navbar.svelte';

</script>

<main class="flex flex-col h-screen divide-y">
	<Navbar />
	<div class="p-8 mb-auto">
		<slot />
	</div>
	<Footer />
</main>

<style lang="postcss">
</style>
