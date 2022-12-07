<script lang="ts">
	import SpaceCat from '$lib/images/space-cat.png'
	let moneyRaised: string = '3,000,000'
	let target: string = '6,000,000'
	let percent: string = '50%'
</script>

<!-- DATA -->

<div class="grid lg:grid-cols-2 w-full gap-4">
	<!-- COL -->
	<div
		id="spaceCat"
		class="border border-white/20 text-white p-4 rounded grid place-items-center h-96"
	/>
	<!-- COL -->
	<div class="border border-white/20 text-white p-4 rounded grid place-content-between">
		<div>
			<h1 class="text-sm uppercase font-bold">About Hodlonaut</h1>
			<p class="text-2xl font-bold my-4">
				Taco pleb. Hodling. Always looking to learn. Speaking my mind. Editing
			</p>
		</div>
		<div class="lg:flex lg:space-x-4">
			<a
				href="https://defendingbtc.com"
				class="btn btn-outline"
				rel="noopener noreferrer"
				target="_blank">@defendingbtc</a
			>
			<a
				href="https://twitter.com/hodlonaut"
				class="btn btn-outline"
				rel="noopener noreferrer"
				target="_blank">@hodlonaut</a
			>
			<a
				href="https://www.citadel21.com/"
				class="btn btn-outline"
				rel="noopener noreferrer"
				target="_blank">@citadel21</a
			>
		</div>
	</div>
</div>

<div class="stats shadow my-8 rounded bg-black border border-white/20 w-full">
	<div class="stat">
		<div class="stat-figure text-primary">
			<svg
				xmlns="http://www.w3.org/2000/svg"
				fill="none"
				viewBox="0 0 24 24"
				class="inline-block w-8 h-8 stroke-current"
				><path
					stroke-linecap="round"
					stroke-linejoin="round"
					stroke-width="2"
					d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z"
				/></svg
			>
		</div>
		<p class="stat-title uppercase">Total Likes</p>
		<div class="stat-value text-primary">25.6K</div>
		<div class="stat-desc">21% more than last month</div>
	</div>

	<div class="stat">
		<div class="stat-figure text-secondary">
			<svg
				xmlns="http://www.w3.org/2000/svg"
				fill="none"
				viewBox="0 0 24 24"
				class="inline-block w-8 h-8 stroke-current"
				><path
					stroke-linecap="round"
					stroke-linejoin="round"
					stroke-width="2"
					d="M13 10V3L4 14h7v7l9-11h-7z"
				/></svg
			>
		</div>
		<p class="stat-title uppercase">Pledges</p>
		<div class="stat-value text-secondary">2.1M</div>
		<div class="stat-desc">21% more than last month</div>
	</div>

	<div class="stat">
		<p class="stat-title uppercase">target</p>
		<div class="stat-value">
			{percent}
		</div>
		<div class="stat-desc text-secondary">
			{target}
		</div>
	</div>
</div>

<div class="grid lg:grid-cols-3 gap-4 w-full">
	<!-- COL1 -->
	<div class="border border-white/20 p-4 shadow-xl rounded">
		<h1 class="uppercase text-sm font-bold text-white">Money Raised</h1>
		<p class="text-4xl font-black text-orange-500 my-2">$ {moneyRaised}</p>
	</div>
	<!-- ACTION BUTTONS -->
	<div class="lg:col-span-2 border border-white/20 text-white p-4 rounded">
		<h1 class="text-sm uppercase font-bold">Get involved</h1>
		<div class="py-4 flex items-center space-x-4">
			<button class="btn bg-blue-500 text-white">Donate</button>
			<button class="btn btn-primary">Bid</button>
			<button class="btn btn-outline">Share</button>
		</div>
	</div>
</div>

<style>
	#spaceCat {
		background-image: url('../../../lib/images/space-cat.png');
		background-position: top;
		background-repeat: no-repeat;
		background-size: cover;
	}
</style>
