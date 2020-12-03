<template>
  <div class="container mx-auto mt-32">
    <section>
      <div class="px-4 sm:px-6 md:px-8 mb-10 sm:mb-16 md:mb-20 text-center">
        <h2
          class="sm:text-lg sm:leading-snug font-semibold tracking-wide uppercase mb-3"
        >
          Boilerplate
        </h2>
        <p
          class="text-3xl sm:text-5xl lg:text-6xl leading-none font-extrabold text-gray-900 tracking-tight mb-8"
        >
          Laravel 8 - Vue 3 - TailwindCSS 2
        </p>
        <p
          class="max-w-4xl text-base sm:text-xl font-medium sm:leading-10 space-y-6 mb-6"
        >
          Full setup
          <span class="bg-gray-200 rounded-full px-4 py-1 mx-2"
            >Laravel Framework 8.17.0</span
          >
          <span class="bg-gray-200 rounded-full px-4 py-1 mx-2">Vue 3.0.3</span>
          <span class="bg-gray-200 rounded-full px-4 py-1 mx-2"
            >TailwindCSS 2.0.1</span
          >

          blank boilerplate for developers, that will save your time :)
        </p>
        <p
          class="max-w-4xl text-lg sm:text-2xl font-medium sm:leading-10 space-y-6 mb-6"
        >
          Have fun!
        </p>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  mounted() {
    console.log("Laravel, Vue, TailwindCSS");
  },
};
</script>
