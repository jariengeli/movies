<script>
	import "./styles.css";

	let { children } = $props();
</script>

<div class="container">
	<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
		<div class="container-fluid">
			<a class="navbar-brand text-white fw-bold" href="/">ScreenStack</a>

			<ul class="navbar-nav me-auto">
				<li class="nav-item">
					<a class="nav-link text-white-50" href="/movies">Movies</a>
				</li>
			</ul>
		</div>
	</nav>

	{@render children()}
</div>
