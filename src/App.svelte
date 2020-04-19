<script>
  import Tailwindcss from './tailwindcss.svelte';
</script>

<main class="w-full h-full text-center flex text-gray-600">
	<div class="container w-2/3 max-w-lg mx-auto text-xl relative">
    <img class="my-8 mx-auto w-full" src="/welcome.svg" alt="Welcome image by unDraw">
    <p class="text-xl my-4">This is a Tailwindcss template project <i>ready-to-use</i></p>
    <div class="card flex flex-row items-center mt-8 justify-center">
      <img class="w-56" src="/coder.svg" alt="Coder illustration by unDraw">
      <p class="ml-8 text-left">Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
    </div>
    <div class="card flex flex-row items-center mt-12 mx-auto justify-center">
      <img class="w-56" src="/tailwindcss.svg" alt="Coder illustration by unDraw">
      <p class="ml-8 text-left">Visit the <a href="https://tailwindcss.com/docs/utility-first">Tailwind CSS</a> page to learn how to use Tailwind</p>
    </div>
    <p class="bottom-0 absolute w-full text-center my-4">You can check theses illustrations in <b><a href="https://undraw.co">undraw.co</a></b></p>
  </div>
</main>