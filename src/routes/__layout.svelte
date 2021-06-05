<script lang="ts">
	import '../global.postcss';
	import Footer from '$lib/Footer.svelte';
	import Navbar from '$lib/Navbar.svelte';

</script>

<main>
	<Navbar />
	<div class="p-8">
		<slot />
		<Footer />
	</div>
</main>

<style lang="postcss">
</style>
