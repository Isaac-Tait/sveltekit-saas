<script>
	import '../app.postcss';
</script>

<header>
	<img src="logo.svg" alt="logo" />

	<nav>
		<a href="/">Home</a>
		<a href="/pricing">Pricing</a>
		<button>Sign In</button>
	</nav>
</header>

<main>
	<slot />
</main>
