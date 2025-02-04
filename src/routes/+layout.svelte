<script>
	import '../app.css';
	let { children } = $props();
</script>

<header>
    Header
</header>

<main>
    {@render children()}
</main>

<footer>
    Footer 
</footer>