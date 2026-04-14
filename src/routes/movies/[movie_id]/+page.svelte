<script>
    let { data } = $props()
</script>


<h1>{data.movie.title}</h1>

<img src= {data.movie.poster} alt={data.movie.title} height="350" width="300px">
<p>Jahr: {data.movie.year}</p>
<p>Dauer: {data.movie.length}</p>
<p>Cast: {data.movie.actors}</p>
