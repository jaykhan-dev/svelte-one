<script>
	import Counter from './Counter.svelte'
	import welcome from '$lib/images/svelte-welcome.webp'
	import welcome_fallback from '$lib/images/svelte-welcome.png'
	import { fade } from 'svelte/transition'
</script>

<svelte:head>
	<title>Plebian Market</title>
	<meta name="description" content="Plebian Market" />
</svelte:head>

<section transition:fade class="py-20">
	<h1 class="text-4xl text-center my-8">
		<span class="welcome">
			<picture>
				<source srcset={welcome} type="image/webp" />
				<img src={welcome_fallback} alt="Welcome" />
			</picture>
		</span>

		Svelte is cool!
	</h1>

	<h2>Built with Tailwind + DaisyUI</h2>

	<Counter />

	<div>
		<button class="btn btn-primary">Button</button>
	</div>
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	h1 {
		width: 100%;
	}

	.welcome {
		display: block;
		position: relative;
		width: 100%;
		height: 0;
		padding: 0 0 calc(100% * 495 / 2048) 0;
	}

	.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	}
</style>
