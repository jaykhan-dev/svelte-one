<script>
	import Carousel from './Carousel.svelte'

	let category = 'funding'
</script>

<svelte:head />

<Carousel />
<div class="grid place-items-center my-8">
	<h1 class="lg:text-5xl my-4">Find it first here</h1>
	<p class="my-4 lg:w-1/3 text-center">
		Indiegogo is where early adopters and innovation seekers find lively, imaginative tech before it
		hits the mainstream.
	</p>
	<div class="space-x-4 my-4">
		<a href="/" class="btn">Sign up now</a>
		<a href="/" class="btn">Learn more</a>
	</div>
</div>
