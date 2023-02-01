<script>
	import MdMoreVert from 'svelte-icons/md/MdMoreVert.svelte';
</script>

<nav class="center-between">
	<a href="/">Flip</a>
	<a href="/about">Words</a>
	<a href="/settings">
		<div class="icon">
			<MdMoreVert />
		</div>
	</a>
</nav>

<slot />

<footer>Version</footer>

<style>
	.icon {
		color: var(--color-primary-txt);
		width: 24px;
		height: 24px;
	}
	nav {
		padding: 1rem;
		background: var(--color-primary);
	}

	nav a {
		color: var(--color-primary-txt);
		text-decoration: none;
		font-weight: bold;
	}

	nav a:hover,
	.icon:hover {
		color: var(--color-primary-hover);
	}

	footer {
		padding: 1rem;
		background: var(--color-primary);
		color: var(--color-primary-txt);
		text-align: center;
	}
</style>
