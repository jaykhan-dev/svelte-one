<script>
	import Carousel from './Carousel.svelte'

	let category = 'funding'
</script>

<svelte:head />

<Carousel />
<div class="grid place-items-center my-8">
	<h1 class="lg:text-5xl my-4">Find it first here</h1>
	<p class="my-4 lg:w-1/3 text-center">Plebeian Market is how you can support other Bitcoiners.</p>
	<div class="space-x-4 my-4">
		<a href="/" class="btn">Make a Bid</a>
		<a href="/" class="btn">Donate</a>
	</div>
</div>
