<script>
  import "../app.postcss";
</script>

<nav class="fixed bg-white top-5 left-1/4 h-12 w-2/3 rounded-full p-2 border-4 border-black border-opacity-5 z-50">
  <button class=" rounded-full w-12 bg-yellow-200 h-full">+</button>
  <span class=" text-yellow-400 col-span-7 font-black">Hello world</span>
  <button class=" bg-gray-200 h-6 w-6 rounded-full float-right">P</button>
</nav>

<div class=" grid grid-cols-12 grid-rows-1">
  <div class="col-span-2 bg-gray-50 h-screen overflow-y-scroll flex flex-col">
    <div class=" bg-gray-200 h-20 w-full text-3xl font-black pl-2">
      <span class="text-pink-400">Donut</span> Planet
    </div>
    <div class=" bg-gray-300 text-xl pl-3">
      You have <span class="font-bold">376</span> sprinkles
    </div>
    {#each new Array(50) as _, n}
      <button class="p-2 px-5 my-4 mx-auto bg-gray-100 text-center rounded-full">Hello world</button>
    {/each}
  </div>
  <div class="col-span-10 h-screen overflow-y-scroll pt-20">
    <slot />
  </div>
</div>