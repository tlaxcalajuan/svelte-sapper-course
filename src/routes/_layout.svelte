<script>
    import Header from './../components/Header.svelte';
    export let segment;
</script>

<main>
    <Header {segment}></Header>
    <slot/>
</main>