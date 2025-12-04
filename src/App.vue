<script setup>
const handleClick = () => {
  alert('Hello from Vue!')
}
</script>

<template>
  <div class="min-h-screen flex items-center justify-center p-4" style="background: #6C8EF5;">
    <div class="bg-white bg-opacity-90 rounded-2xl shadow-2xl p-8 max-w-md w-full text-center">
      <h1 class="text-4xl font-bold text-pink-300 mb-6" style="-webkit-text-stroke: 2px orange; text-stroke: 2px orange;">
        Hello World 💣
      </h1>
      <button
        @click="handleClick"
        class="bg-lime-400 hover:bg-lime-500 text-black font-bold py-3 px-8 rounded-lg transition-all duration-200 shadow-lg shadow-lime-400/50 hover:shadow-xl hover:shadow-lime-500/60"
        style="box-shadow: 0 0 20px rgba(163, 230, 53, 0.6), 0 0 40px rgba(163, 230, 53, 0.3);"
      >
        Click me
      </button>
    </div>
  </div>
</template>
