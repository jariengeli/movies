<script>
    import Film from "$lib/components/Film.svelte";

    let { data } = $props();

</script>

<div class="container mt-4">
    <p class="text-white-50 fst-italic mb-4">
        Daten und Bilder generiert mit KI
    </p>
    
<a href="/movies/create" class="btn btn-primary mb-3"> Add New Movie </a>

    <div class="row row-cols-1 row-cols-md-2 row-cols-lg-4 g-4">
        {#each data.movies as movie}
            <Film {movie} />
        {/each}
    </div>
</div>
