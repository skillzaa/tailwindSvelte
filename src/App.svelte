<script>
  export let name;
</script>

<main class="text-center p-4 max-w-xs mx-auto sm:max-w-none">
  <h1 class="text-yellow-400 text-6xl uppercase leading-loose font-thin bg-green-800">Hello {name}!</h1>
  <p class="text-blue-800">
    Visit the <a class="text-blue-500 hover:underline" href="https://svelte.dev/tutorial">
    Svelte tutorial</a> to learn how to build Svelte apps.
  </p>
</main>

<style lang="postcss" global>
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
</style>
