<script>
	import { page } from '$app/stores'
	import logo from '$lib/images/svelte-logo.svg'
	import github from '$lib/images/github.svg'
</script>

<header class="fixed top-0 w-full shadow-2xl z-50 border-b border-white/20">
	<div class="navbar bg-gray-900">
		<div class="navbar-start">
			<div class="dropdown">
				<svg
					xmlns="http://www.w3.org/2000/svg"
					class="h-5 w-5"
					fill="none"
					viewBox="0 0 24 24"
					stroke="currentColor"
					><path
						stroke-linecap="round"
						stroke-linejoin="round"
						stroke-width="2"
						d="M4 6h16M4 12h8m-8 6h16"
					/></svg
				>

				<ul class="menu menu-compact dropdown-content mt-3 p-2 shadow bg-base-100 rounded-box w-52">
					<li><a href="/">Item 1</a></li>
					<li>
						<a href="/" class="justify-between">
							Parent
							<svg
								class="fill-current"
								xmlns="http://www.w3.org/2000/svg"
								width="24"
								height="24"
								viewBox="0 0 24 24"
								><path d="M8.59,16.58L13.17,12L8.59,7.41L10,6L16,12L10,18L8.59,16.58Z" /></svg
							>
						</a>
						<ul class="p-2">
							<li><a href="/">Submenu 1</a></li>
							<li><a href="/">Submenu 2</a></li>
						</ul>
					</li>
					<li><a href="/">Item 3</a></li>
				</ul>
			</div>
			<a href="/" class="btn btn-ghost normal-case text-xl">Plebeian Market</a>
		</div>
		<div class="navbar-center hidden lg:flex">
			<ul class="menu menu-horizontal p-0">
				<li>
					<a href="/hodlonaut">
						Campaign
						<svg
							class="fill-current"
							xmlns="http://www.w3.org/2000/svg"
							width="20"
							height="20"
							viewBox="0 0 24 24"
							><path d="M7.41,8.58L12,13.17L16.59,8.58L18,10L12,16L6,10L7.41,8.58Z" /></svg
						>
					</a>
					<ul class="p-2">
						<li class="bg-black"><a href="/campaign/hodlonaut">Hodlonaut</a></li>
						<li class="bg-black"><a href="/campaign/auction">Auction</a></li>
					</ul>
				</li>
				<li>
					<a href="/">
						Scenes
						<svg
							class="fill-current"
							xmlns="http://www.w3.org/2000/svg"
							width="20"
							height="20"
							viewBox="0 0 24 24"
							><path d="M7.41,8.58L12,13.17L16.59,8.58L18,10L12,16L6,10L7.41,8.58Z" /></svg
						>
					</a>
					<ul class="p-2">
						<li class="bg-black"><a href="/scenes/one">Scene One</a></li>
						<li class="bg-black"><a href="/scenes/two">Scene Two</a></li>
					</ul>
				</li>
				<li><a href="/data">Data</a></li>
			</ul>
		</div>
		<div class="navbar-end flex items-center space-x-4">
			<input type="checkbox" class="toggle toggle-lg" checked />
			<div class="avatar">
				<div class="w-8 rounded-full ring ring-primary ring-offset-base-50 ring-offset-2">
					<img src="https://placeimg.com/192/192/people" alt="avatar daisy ui" />
				</div>
			</div>
		</div>
	</div>
</header>
