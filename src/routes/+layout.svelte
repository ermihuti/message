<script>
    // Import the global CSS file for styling
    import '../app.css';
    
    // Destructure the children prop from the component's props
    let { children } = $props();
</script>

<header>
    <!-- Static header content -->
    Header
</header>

<main>
    <!-- Render the children passed to this layout component -->
    {@render children()}
</main>

<footer>
    <!-- Static footer content -->
    Footer
</footer>