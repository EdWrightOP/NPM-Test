<script>
    import Footer from "$lib/Footer.svelte";
    import Header from "../lib/Header.svelte";
</script>
<Header/>
<h1>Welcome to SvelteKit</h1>

<Footer year={1500}/>
<br>
<Footer year = {1922}/>
<Footer year = {2083}/>
<Footer year = {5005}/>

<style>
    :global(*){
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    }
</style>