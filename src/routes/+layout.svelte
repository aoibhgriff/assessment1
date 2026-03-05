<script>
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';
    import Footer from "$lib/components/Footer.svelte";
    import Nav from "$lib/components/Nav.svelte";
    import Header from "$lib/components/Header.svelte";
	
    let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>

<Header />
<Nav />

{@render children()}

<Footer />

<style>
    :global(body) {
        background-color: black;
        color: white;
    }
</style>