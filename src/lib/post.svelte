<script>
	export let post_id;

	let comment_placeholder = [];
</script>

<div class="border-2 border-black mx-12 my-12 px-9 py-3 rounded-3xl ">
	<span class=" font-black text-3xl">Hello</span>
	<p class="mb-4">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Delectus ducimus doloribus dolorem, modi nobis laudantium vel ab! Accusamus cum quaerat quasi quo quas pariatur, incidunt atque corporis nam laboriosam earum!</p>
	
	<form class="flex">
		<input type="text" name="comment" id="comment" placeholder="Speak your mind..." class="w-full border-b-2 border-gray-300 bg-transparent focus-within:border-black transition-colors rounded-bl-lg">
		<button class=" w-6 border-b-2 border-gray-300 rounded-br-lg">+</button>
	</form>
</div>