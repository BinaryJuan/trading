<script>
    import Navbar from "../components/Navbar.svelte"
    import Home from "../components/Home.svelte";
    import Services from "../components/Services.svelte";
    import Brands from "../components/Brands.svelte";
    import Products from "../components/Products.svelte";
    import Contact from "../components/Contact.svelte";
    import Footer from "../components/Footer.svelte";
</script>

<main>
    <Navbar />
    <Home />
    <Services />
    <Brands />
    <Products />
    <Contact />
    <Footer />
</main>

<style>
    :global(html) {
        scroll-behavior: smooth;
    }
    :global(body) {
        margin: 0;
        font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
    :global(h2) {
        margin: 0;
    }
    :global(h3) {
        margin: 0;
    }
    :global(h4) {
        margin: 0;
    }
    :global(p) {
        margin: 0;
    }
</style>