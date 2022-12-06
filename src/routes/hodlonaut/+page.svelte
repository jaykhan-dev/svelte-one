<script>
</script>

<svelte:head>
	<title>Services</title>
	<meta name="services" content="Services SEO" />
</svelte:head>

<div class="grid place-items-center text-black lg:w-2/3 mx-auto my-20 py-20">
	<div class="p-4 bg-sky-400 rounded shadow-xl w-full grid place-items-center py-20 my-20">
		<h1 class="lg:text-9xl font-black">Services</h1>
		<p>We offer services to help you succeed.</p>
	</div>
	<div class="grid lg:grid-cols-3 my-8 gap-4 w-full">
		<!-- COL1 -->
		<div class="bg-green-400 p-4 shadow-xl rounded">
			<h1 class="font-black text-2xl">Svelte UI</h1>
			<p>Fast, performant, accessible, responsive</p>
		</div>
		<!-- COL2 -->
		<div class="lg:col-span-2 bg-purple-400 p-4 rounded">
			<h1>Col</h1>
			<button class="btn">Button</button>
		</div>
	</div>

	<div class="grid lg:grid-cols-2 w-full gap-4">
		<!-- COL1 -->
		<div class="bg-blue-400 p-4 rounded h-64">
			<h1>NEW SERVICE</h1>
		</div>
		<!-- COL2 -->
		<div class="bg-yellow-400 p-4 rounded h-64">
			<h1>DESCRIPTION</h1>
		</div>
	</div>
</div>

<div class="hero bg-orange-200 text-black my-20 py-20">
	<div class="hero-content text-center">
		<div class="max-w-md">
			<h1 class="text-5xl font-bold">Hello there</h1>
			<p class="py-6">
				Provident cupiditate voluptatem et in. Quaerat fugiat ut assumenda excepturi exercitationem
				quasi. In deleniti eaque aut repudiandae et a id nisi.
			</p>
			<button class="btn btn-primary">Get Started</button>
		</div>
	</div>
</div>

<div class="collapse lg:w-2/3 mx-auto rounded">
	<input type="checkbox" class="peer" />
	<div
		class="collapse-title bg-primary text-primary-content peer-checked:bg-secondary peer-checked:text-secondary-content"
	>
		Click me to show/hide content
	</div>
	<div
		class="collapse-content bg-primary text-primary-content peer-checked:bg-secondary peer-checked:text-secondary-content"
	>
		<p>hello</p>
	</div>
</div>

<div class="stats shadow bg-white my-8 rounded text-black lg:w-2/3 grid lg:grid-cols-3 mx-auto">
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
		<div class="stat-title">Page Views</div>
		<div class="stat-value text-secondary">2.6M</div>
		<div class="stat-desc">21% more than last month</div>
	</div>

	<div class="stat">
		<div class="stat-figure text-secondary">
			<div class="avatar online">
				<div class="w-16 rounded-full">
					<img src="https://placeimg.com/128/128/people" alt="daisy ui" />
				</div>
			</div>
		</div>
		<div class="stat-value">86%</div>
		<div class="stat-title">Tasks done</div>
		<div class="stat-desc text-secondary">31 tasks remaining</div>
	</div>
</div>
