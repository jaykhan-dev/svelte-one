<script lang="ts">
	import { fade } from 'svelte/transition'
	import Auctions from './Auctions.svelte'
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
		<div class="hero-content text-white">
			<div class="grid lg:grid-cols-2">
				<div>
					<h1 class="text-8xl font-bold">Hodlonaut</h1>

					<p class="my-4">
						Whilst we can celebrate Hodlonaut's win in Oslo, the legal battle continues. The British
						legal process is a much bigger event in both time and money.
					</p>
					<p class="my-4">
						This campaign is to provide the Bitcoin community with a perpetual fund raising
						capability whereby anyone can raise money by selling anything physical or their time for
						either a fixed price or an auction (within the laws of the UK).
					</p>
					<div class="flex space-x-4 my-8">
						<button class="btn btn-primary">Auction 1-hour</button>
						<button class="btn btn-secondary">Auction Item</button>
						<button class="btn btn-outline">Fixed Price</button>
					</div>
				</div>
			</div>
		</div>
	</div>
</div>

<!-- <div transition:fade class="grid place-items-center text-black lg:w-2/3 mx-auto py-20 p-4">
	<Grid />
</div> -->

<Auctions />

<style>
	#bgTwo {
		background-image: url('../../../lib/images/moon-landscape.jpg');
		background-repeat: no-repeat;
		background-size: cover;
		background-position: center;
		height: 650px;
	}
</style>
