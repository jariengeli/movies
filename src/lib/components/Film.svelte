<script>
    let { movie } = $props();
</script>

<div class="card bg-dark text-white h-100 border-secondary">
    <img 
        src={movie.poster} 
        class="card-img-top" 
        alt={`Poster für ${movie.Title}`} 
    />
    
    <div class="card-body">
        <h5 class="card-title fw-bold"> <a href={"/movies/"+movie._id}>{movie.title}</a></h5>
        <p class="card-text mb-1 text-light">Jahr: {movie.year}</p>
        <p class="card-text text-light">Dauer: {movie.length}</p>
    </div>
</div>