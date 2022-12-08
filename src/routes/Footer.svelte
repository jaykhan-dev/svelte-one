<script lang="ts">
	import Logo from '../lib/images/pleb-logo-white.svg'
	import Substack from '../lib/images/substack.svg'
</script>

<svelte:head>
	<link
		rel="stylesheet"
		href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css"
		integrity="sha512-MV7K8+y+gLIBoVD59lQIYicR65iaqukzvf/nwasF0nqhPay5w/9lJmVM2hMDcnK1OnMGCdVK+iQrJ7lzPJQd1w=="
		crossorigin="anonymous"
		referrerpolicy="no-referrer"
	/>
</svelte:head>

<footer class="text-white mt-32 lg:p-0 p-4">
	<!-- SIGNUP -->

	<div
		class="my-8 lg:flex items-center justify-between p-6 rounded shadow-xl lg:w-2/3 mx-auto bg-gradient-to-r from-violet-500 via-blue-600 to-sky-500"
	>
		<div>
			<h1 class="lg:text-4xl text-3xl font-bold">Get regular updates</h1>
			<div class="lg:flex lg:space-x-4 my-6">
				<p>&#10003; Weekly</p>
				<p>&#10003; New Releases</p>
				<p>&#10003; New Deals</p>
			</div>
		</div>
		<div class="flex items-center space-x-4">
			<button class="btn border-2 border-white"> Sign up free &#8702;</button>
			<button class="btn border-2 border-white">Contact team &#8702;</button>
		</div>
	</div>

	<!-- DISCLAIMERS -->
	<div class="">
		<div class="lg:w-2/3 mx-auto lg:flex items-center justify-between py-6">
			<div class="flex items-center space-x-4">
				<p>Powered by</p>
				<a href="https://plebian.technology" class="btn">Plebian Technology</a>
			</div>
			<div class="text-2xl flex items-center space-x-4 lg:my-0 my-4">
				<i class="fa-brands fa-twitter" />
				<i class="fa-brands fa-telegram" />
				<i class="fa-brands fa-github" />
				<img src={Substack} alt="substack" width={19} />
			</div>
		</div>
	</div>
</footer>

<style>
</style>
