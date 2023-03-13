<script>
	import '../app.postcss';
</script>

<header>
	<img src="logo.svg" alt="logo" />

	<nav>
		<a href="/dashboard">Home</a>
		<a href="/billing">Billing</a>
		<button>Sign Out</button>
	</nav>
</header>

<main>
	<slot />
</main>
