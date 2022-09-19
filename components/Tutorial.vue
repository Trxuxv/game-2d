<!-- Please remove this file from your project -->
<template>
  <div
    class="relative flex items-top justify-center min-h-screen bg-gray-800 sm:items-center sm:pt-0 h-screen"
  >
    <link
      href="https://cdn.jsdelivr.net/npm/tailwindcss@2.1.2/dist/tailwind.min.css"
      rel="stylesheet"
    />
    <div class="max-w-4xl mx-auto sm:px-6 lg:px-8 h-4/5 w-5/6">
      <div
        class="mt-8 bg-white overflow-hidden shadow sm:rounded-lg p-4 bg-gray-900 text-gray-100"
      >
        Choose character:
        <div class="bg-gray-500 w-full grid grid-cols-6 gap-4 p-2">
          <div class="bg-black h-28 rounded-lg">1</div>
          <div class="bg-black h-28 rounded-lg">1</div>
          <div class="bg-black h-28 rounded-lg">1</div>
          <div class="bg-black h-28 rounded-lg">1</div>
          <div class="bg-black h-28 rounded-lg">1</div>
          <div class="bg-black h-28 rounded-lg">1</div>
          <div class="bg-black h-28 rounded-lg">1</div>
          <div class="bg-black h-28 rounded-lg">1</div>
          <div class="bg-black h-28 rounded-lg">1</div>
          <div class="bg-black h-28 rounded-lg">1</div>
          <div class="bg-black h-28 rounded-lg">1</div>
          <div class="bg-black h-28 rounded-lg">1</div>
          <div class="bg-black h-28 rounded-lg">1</div>
          <div class="bg-black h-28 rounded-lg">1</div>
          <div class="bg-black h-28 rounded-lg">1</div>
          <div class="bg-black h-28 rounded-lg">1</div>
          <div class="bg-black h-28 rounded-lg">1</div>
          <div class="bg-black h-28 rounded-lg">1</div>
        </div>
        <p class="mt-4 pt-4 text-gray-800 border-t border-dashed text-center">
          <button @click="start()"
            class="border border-gray-100 bg-gray-800 rounded-lg text-white p-2 px-6 text-sm"
          >
            START
          </button>
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "NuxtTutorial",
  methods: {
    start() {
      this.$router.push("started");
    },
  },
};
</script>
