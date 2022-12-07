<script>
	import Header from './Header.svelte'
	import Footer from './Footer.svelte'
	import '../app.css'

	let dark = true
</script>

<div>
	<Header />

	<main class="">
		<slot />
	</main>

	<Footer />
</div>
