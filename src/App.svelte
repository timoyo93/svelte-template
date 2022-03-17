<script lang="ts">
  export let name: string;
</script>

<main>
  <div class="flex h-[100vh] justify-center items-center">
    <div class="text-center">
      <h1 class="text-4xl text-red-500">Hello {name}!</h1>
      <p>
        Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn
        how to build Svelte apps.
      </p>
    </div>
  </div>
</main>

<style global lang="postcss">
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
</style>
