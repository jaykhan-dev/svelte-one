<script lang="ts">
	import { fade } from 'svelte/transition'
	import { onMount } from 'svelte'
	const endpoint = 'https://api.coinlore.net/api/ticker/?id=90'

	interface BitcoinData {
		id: string
		price_usd: string
		percent_change_24h: string
		rank: number
	}

	let ticker: BitcoinData[] = []

	onMount(async function () {
		const res = await fetch(endpoint)
		const data = await res.json()
		console.log(data)
		ticker = data.slice(0, 10)
	})
</script>

<div transition:fade class="text-white lg:w-2/3 mx-auto min-h-screen">
	<div class="mt-20">
		<h1 class="text-2xl font-black">BTC Price:</h1>
	</div>

	<div class="">
		{#each ticker as data}
			<div class="border-b border-white/20 py-10">
				<h1 class="text-6xl my-4 font-bold text-gray-600">${data.price_usd}</h1>
				<p>Pulled from the CoinLore API</p>
			</div>
		{/each}
	</div>
</div>
