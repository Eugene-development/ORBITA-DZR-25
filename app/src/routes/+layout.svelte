<script>
	import '../app.css';
	let { children } = $props();
</script>

<nav>
	<a href="/">Home</a>
	<a href="/about">About</a>
	<a href="/contact">Контакты</a>
</nav>

{@render children()}

<p>футер</p>