<script>
	import SpaceCat from '$lib/images/space-cat.png'

	// let date = new Date()
</script>

<svelte:head>
	<script src="https://unpkg.com/@lottiefiles/lottie-player@latest/dist/lottie-player.js"></script>
</svelte:head>

<div class="grid place-items-center lg:w-2/3 mx-auto text-center py-20 p-4">
	<div class="flex justify-center" />
	<h1 class="lg:text-6xl text-4xl font-black my-8">Auctions</h1>
	<p>Latest form a variety of sources</p>

	<!-- <div class="tabs tabs-boxed">
		<a class="tab">Tab 1</a>
		<a class="tab">Tab 2</a>
		<a class="tab">Tab 3</a>
	</div> -->

	<div class="grid lg:grid-cols-4 gap-4 my-20">
		<!-- CARD -->
		<div class="card border border-white/20">
			<figure><img src={SpaceCat} alt="car!" /></figure>
			<div class="card-body">
				<p class="w-full text-left text-sm font-mono text-gray-500">2022-01-03</p>
				<h2 class="card-title text-3xl">Story one</h2>
				<p class="text-left">The latest news on the status of the court case</p>
				<div class="card-actions justify-start">
					<button class="uppercase font-bold mt-8">Read Story</button>
				</div>
			</div>
		</div>

		<!-- CARD -->
		<div class="card border border-white/20">
			<figure><img src={SpaceCat} alt="car!" /></figure>
			<div class="card-body">
				<p class="w-full text-left text-sm font-mono text-gray-500">2022-01-03</p>
				<h2 class="card-title text-3xl">Story two</h2>
				<p class="text-left">Hodlonaut wins case against Craig Wright in Norway!</p>
				<div class="card-actions justify-start">
					<button class="uppercase font-bold mt-8">Read Story</button>
				</div>
			</div>
		</div>

		<!-- CARD -->
		<div class="card border border-white/20">
			<figure><img src={SpaceCat} alt="car!" /></figure>
			<div class="card-body">
				<p class="w-full text-left text-sm font-mono text-gray-500">2022-01-03</p>
				<h2 class="card-title text-3xl">Story three</h2>
				<p class="text-left">The situation on the ground in Great Britain</p>
				<div class="card-actions justify-start">
					<button class="uppercase font-bold mt-8">Read Story</button>
				</div>
			</div>
		</div>

		<!-- CARD -->
		<div class="card border border-white/20">
			<figure><img src={SpaceCat} alt="car!" /></figure>
			<div class="card-body">
				<p class="w-full text-left text-sm font-mono text-gray-500">2022-01-03</p>
				<h2 class="card-title text-3xl">Story four</h2>
				<p class="text-left">New developments in the case against Craig Wright</p>
				<div class="card-actions justify-start">
					<button class="uppercase font-bold mt-8">Read Story</button>
				</div>
			</div>
		</div>
	</div>
</div>
