<script lang="ts">
	import { fade } from 'svelte/transition'
	import News from './News.svelte'
	import Faq from './FAQ.svelte'
	import Grid from './Grid.svelte'
</script>

<svelte:head>
	<title>Hodlonaut Campaign</title>
	<meta name="services" content="Services SEO" />
</svelte:head>

<!-- HERO2-->
<div transition:fade id="bgTwo" class="hero bg-fixed">
	<div class="bg-gradient-to-b from-black/20 to-black w-full h-full py-20 grid place-items-center">
		<div class="hero-content text-center text-white">
			<div class="max-w-md">
				<h1 class="text-5xl font-bold">Hodlonaut</h1>
				<p class="py-6 text-2xl my-4">Brief description of the campaign</p>
				<div class="flex space-x-4 justify-center my-8">
					<button class="btn btn-primary">Donate</button>
					<button class="btn btn-primary">Make a Bid</button>
				</div>
			</div>
		</div>
	</div>
</div>

<div transition:fade class="grid place-items-center text-black lg:w-2/3 mx-auto py-20 p-4">
	<Grid />
</div>

<News />

<Faq />

<style>
	#bgTwo {
		background-image: url('../../../lib/images/moon-landscape.jpg');
		background-repeat: no-repeat;
		background-size: cover;
		background-position: center;
		height: 650px;
	}
</style>
