<template>
  <div id="app" class="bg-white py-8">
    <div class="container mx-auto px-8">
      <h2 class="text-2xl font-bold text-black mb-2">CSS Grid Utilities</h2>
      <p class="mb-6">
        <a href="https://github.com/tailwindcss/plugin-examples#css-grid-utilities" class="text-sm text-blue no-underline hover:underline">Learn more</a>
        <span class="mx-1">·</span>
        <a href="https://github.com/tailwindcss/plugin-examples/blob/master/plugins/css-grid/index.js" class="text-sm text-blue no-underline hover:underline">View plugin source</a>
      </p>
      <div class="mb-8">
        <h3 class="text-xl font-bold text-black mb-6">Auto-column sizes</h3>
        <div class="mb-4">
          <code class="block mb-2 text-grey-dark">.grid.grid-columns-2</code>
          <div class="grid grid-columns-2 h-16">
            <div class=""></div>
            <div class=""></div>
          </div>
        </div>
        <div class="mb-4">
          <code class="block mb-2 text-grey-dark">.grid.grid-columns-3</code>
          <div class="grid grid-columns-3 h-16">
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
          </div>
        </div>
        <div class="mb-4">
          <code class="block mb-2 text-grey-dark">.grid.grid-columns-4</code>
          <div class="grid grid-columns-4 h-16">
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
          </div>
        </div>
        <div class="mb-4">
          <code class="block mb-2 text-grey-dark">.grid.grid-columns-5</code>
          <div class="grid grid-columns-5 h-16">
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
          </div>
        </div>
        <div class="mb-4">
          <code class="block mb-2 text-grey-dark">.grid.grid-columns-6</code>
          <div class="grid grid-columns-6 h-16">
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
          </div>
        </div>
        <div class="mb-4">
          <code class="block mb-2 text-grey-dark">.grid.grid-columns-8</code>
          <div class="grid grid-columns-8 h-16">
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
          </div>
        </div>
        <div class="mb-4">
          <code class="block mb-2 text-grey-dark">.grid.grid-columns-10</code>
          <div class="grid grid-columns-10 h-16">
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
          </div>
        </div>
        <div class="mb-4">
          <code class="block mb-2 text-grey-dark">.grid.grid-columns-12</code>
          <div class="grid grid-columns-12 h-16">
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
          </div>
        </div>
      </div>
      <div class="mb-8">
        <h3 class="text-xl font-bold text-black mb-6">Spanning multiple columns</h3>
        <div class="mb-4">
          <code class="block mb-2 text-grey-dark">.grid.grid-columns-12</code>
          <div class="grid grid-columns-12 h-16 mb-4">
            <div class="col-span-8 p-4">
              <code class="block text-grey-darker">.col-span-8</code>
            </div>
            <div class="col-span-4 p-4">
              <code class="block text-grey-darkest">.col-span-4</code>
            </div>
          </div>
        </div>
        <div class="mb-4">
          <code class="block mb-2 text-grey-dark">.grid.grid-columns-5</code>
          <div class="grid grid-columns-5 h-16 mb-4">
            <div class="col-span-2 p-4">
              <code class="block text-grey-darker">.col-span-2</code>
            </div>
            <div class="col-span-3 p-4">
              <code class="block text-grey-darkest">.col-span-3</code>
            </div>
          </div>
        </div>
      </div>
      <div class="mb-8">
        <h3 class="text-xl font-bold text-black mb-6">Explicit start and end points</h3>
        <div class="mb-4">
          <code class="block mb-2 text-grey-dark">.grid.grid-columns-12</code>
          <div class="grid grid-columns-12 grid-dense h-16">
            <div class="col-start-1 col-end-4 p-4">
              <code class="block text-grey-darker">.col-start-1.col-end-4</code>
            </div>
            <div class="col-start-6 col-end-10 p-4">
              <code class="block text-grey-darker">.col-start-6.col-end-10</code>
            </div>
          </div>
        </div>
      </div>
      <div class="mb-8">
        <h3 class="text-xl font-bold text-black mb-6">Gutters</h3>
        <div class="mb-4">
          <code class="block mb-2 text-grey-dark">.grid.grid-columns-3.grid-gap-0</code>
          <div class="grid grid-columns-3 grid-gap-0 h-16 mb-4">
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
          </div>
        </div>
        <div class="mb-4">
          <code class="block mb-2 text-grey-dark">.grid.grid-columns-3.grid-gap-4</code>
          <div class="grid grid-columns-3 grid-gap-4 h-16 mb-4">
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
          </div>
        </div>
        <div class="mb-4">
          <code class="block mb-2 text-grey-dark">.grid.grid-columns-3.grid-gap-8</code>
          <div class="grid grid-columns-3 grid-gap-8 h-16 mb-4">
            <div class=""></div>
            <div class=""></div>
            <div class=""></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  import HelloWorld from './components/HelloWorld.vue'

  export default {
    name: 'app',
    components: {
      HelloWorld
    }
  }
</script>

<style>
@tailwind preflight;
@tailwind components;
@tailwind utilities;

.grid > *:nth-child(odd) {
    background-color: #dae1e7;
}
.grid > *:nth-child(even) {
    background-color: #b8c2cc;
}
</style>
