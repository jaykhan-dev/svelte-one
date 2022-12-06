<script>
	import Header from './Header.svelte'
	import Footer from './Footer.svelte'
	import '../app.css'
</script>

<div class="app bg-black block overflow-x-hidden">
	<Header />

	<main class="">
		<slot />
	</main>

	<Footer />
</div>
