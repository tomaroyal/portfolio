<script lang="ts">
	import ProjectCard from '$lib/ProjectCard.svelte';

</script>

<svelte:head>
	<!-- Primary Meta Tags -->
	<title>Royal Tomar | Portfolio</title>
	<meta name="title" content="Royal Tomar | Portfolio" />
	<meta
		name="description"
		content="I'm a UX designer and creator. You've found my personal space on the internet."
	/>
	<meta name="keywords" content="Svelte, SvelteKit, Svelte-kit, Tailwind, HTML, CSS, JavaScript" />
	<meta name="author" content="@dansvel" />
	<!-- Open Graph / Facebook -->
	<meta property="og:type" content="website" />
	<meta property="og:url" content="https://metatags.io/" />
	<meta property="og:title" content="Royal Tomar | Portfolio" />
	<meta
		property="og:description"
		content="I'm a UX designer and creator. You've found my personal space on the internet."
	/>
	<!-- <meta
    property="og:image"
    content="https://sveltekit-tailwind2.netlify.app/screenshot.png"
  /> -->

	<!-- Twitter -->
	<meta property="twitter:card" content="summary_large_image" />
	<meta property="twitter:url" content="https://metatags.io/" />
	<meta property="twitter:title" content="Royal Tomar | Portfolio" />
	<meta
		property="twitter:description"
		content="I'm a UX designer and creator. You've found my personal space on the internet."
	/>
	<!-- <meta
    property="twitter:image"
    content="https://sveltekit-tailwind2.netlify.app/screenshot.png"
  /> -->
</svelte:head>

<h1 class="text-5xl font-extrabold mb-4">Hey, I'm Royal Tomar</h1>
<p>
	I'm a UX designer, creator. You've found my personal space on the Internet. Here are a few
	projects that I've worked on.
</p>
<h2 class="text-5xl font-extrabold mt-2 mb-2">Projects</h2>

<div class="grid grid-cols-1 md:grid-cols-2 gap-4 md:p-8">
	<ProjectCard />
	<ProjectCard />
	<ProjectCard />
	<ProjectCard />
	<ProjectCard />
	<ProjectCard />
</div>
<div class="aspect-w-1 aspect-h-1 md:aspect-w-16 md:aspect-h-9 my-4 md:my-0">
	<iframe
		src="https://www.youtube.com/embed/QH2RFrOznvw"
		title="anime video"
		frameborder="0"
		allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
		allowfullscreen
	/>
</div>
