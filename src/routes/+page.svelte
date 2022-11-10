<script>
	import Post from "$lib/post.svelte";
</script>

{#each new Array(50) as _}
	<Post />
{/each}