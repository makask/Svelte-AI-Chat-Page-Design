<script>
	import Navbar from "./Navbar.svelte";
	import Header from "./Header.svelte";
	import Main from "./Main.svelte";
	import Footer from "./Footer.svelte";
</script>



<main>
	<div class="nav-container">
		<Navbar />
	</div>
	<div class="main-container">
		<Header />
		<Main />
		<Footer />
	</div>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto; 
		display: flex;
	}

	.main-container {
		display: flex;
		flex-direction: column;
		margin-left: 2%;
	}

	h1 {
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>

