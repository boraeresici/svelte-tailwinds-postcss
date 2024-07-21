<!-- Header.svelte -->
<header class="bg-blue-400light p-1 display: flex flex-wrap justify-end">
	<a href="/">Home</a>

	<nav>
		<ul>
			<li>
				<a href="/blog">Blog</a>
			</li>
			<li>
				<a href="/about">About</a>
			</li>
			<li>
				<a href="/contact">Contact</a>
			</li>
		</ul>
	</nav>
</header>
<!-- ... The rest of the file's contents here -->
<style>
	ul {
		margin: 0;
		list-style-type: none;
		display: flex;
		gap: 1rem;
	}

	a {
		text-decoration: none;
		color: inherit;
	}
</style>