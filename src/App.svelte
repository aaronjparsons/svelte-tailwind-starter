<script>
	import TailwindCSS from './TailwindCSS.svelte';

	export let name;
</script>

<main class="text-center p-4 m-auto">
	<h1 class="text-red-500 uppercase text-6xl font-hairline">Hello {name}!</h1>
	<p>Visit the <a class="text-indigo-500" href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
</main>
<TailwindCSS />


<style type="text/scss"></style>