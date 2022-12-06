<script lang="ts">
	let moneyRaised: string = '3,000,000'
	let target: string = '6,000,000'
	let percent: string = '50%'
</script>

<svelte:head>
	<title>Hodlonaut Campaign</title>
	<meta name="services" content="Services SEO" />
</svelte:head>

<div class="grid place-items-center text-black lg:w-2/3 mx-auto my-20 py-20 p-4">
	<!-- HERO -->
	<div
		id="hodlonautHero"
		class="text-white p-4 bg-sky-400 rounded shadow-xl w-full grid place-items-center py-20 bg-fixed"
	>
		<h1 class="lg:text-9xl font-black">Hodlonaut</h1>
		<p>Help Hodlonaut with this fight against Faketoshi</p>
	</div>

	<!-- DATA -->
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
			<div class="stat-title">Total Likes</div>
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
			<div class="stat-title">Pledges</div>
			<div class="stat-value text-secondary">2.1M</div>
			<div class="stat-desc">21% more than last month</div>
		</div>

		<div class="stat">
			<div class="stat-value">
				{percent}
			</div>
			<div class="stat-title">of target</div>
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
		<!-- COL2 -->
		<div
			class="lg:col-span-2 bg-gradient-to-r from-zinc-800 to-zinc-900 border border-white/20 text-white p-4 rounded"
		>
			<h1 class="text-sm uppercase font-bold">Action buttons</h1>
			<div class="py-4 flex items-center space-x-4">
				<button class="btn bg-blue-500 text-white">Donate</button>
				<button class="btn">Bid</button>
				<button class="btn">Donate</button>
			</div>
		</div>
	</div>

	<div class="grid lg:grid-cols-2 w-full gap-4 my-8">
		<!-- COL1 -->
		<div class="border border-white/20 text-white p-4 rounded h-64">
			<h1 class="text-sm uppercase font-bold">About Hodlonaut</h1>
		</div>
		<!-- COL2 -->
		<div class="border border-white/20 text-white p-4 rounded h-64">
			<h1 class="text-sm uppercase font-bold">The Campaign</h1>
		</div>
	</div>
</div>

<div id="bgTwo" class="hero bg-fixed">
	<div
		class="bg-black/80 w-full h-full border-t border-b border-white/20 py-20 my-20 grid place-items-center"
	>
		<div class="hero-content text-center text-white">
			<div class="max-w-md">
				<h1 class="text-5xl font-bold">Hello there</h1>
				<p class="py-6">
					Provident cupiditate voluptatem et in. Quaerat fugiat ut assumenda excepturi
					exercitationem quasi. In deleniti eaque aut repudiandae et a id nisi.
				</p>
				<button class="btn btn-primary">Get Started</button>
			</div>
		</div>
	</div>
</div>

<!-- FAQ -->
<div class="lg:w-2/3 mx-auto lg:p-0 p-4">
	<h1 class="text-8xl font-black text-center">FAQ</h1>
	<div class="collapse rounded my-4 py-20">
		<input type="checkbox" class="peer" />
		<div
			class="collapse-title bg-primary text-primary-content peer-checked:bg-secondary peer-checked:text-secondary-content"
		>
			<p class="text-3xl font-bold">Click me to show/hide content</p>
		</div>
		<div
			class="collapse-content bg-primary text-primary-content peer-checked:bg-secondary peer-checked:text-secondary-content"
		>
			<p>hello</p>
		</div>
	</div>
</div>

<style>
	#hodlonautHero {
		background-image: url('../../lib/images/moon-landscape.jpg');
		background-repeat: no-repeat;
		background-size: cover;
		background-position: center;
	}

	#bgTwo {
		background-image: url('../../lib/images/hoodies.svg');
		background-repeat: no-repeat;
		background-size: cover;
		background-position: center;
	}
</style>
