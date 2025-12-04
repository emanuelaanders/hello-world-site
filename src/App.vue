<script setup>
const handleClick = () => {
  alert('Hello from Vue!')
}
</script>

<template>
  <div class="min-h-screen bg-gradient-to-br from-blue-50 to-indigo-100 flex items-center justify-center p-4">
    <div class="bg-white rounded-2xl shadow-xl p-8 max-w-md w-full text-center">
      <h1 class="text-4xl font-bold text-red-600 mb-6">
        Hello World
      </h1>
      <button
        @click="handleClick"
        class="bg-blue-600 hover:bg-blue-700 text-white font-semibold py-3 px-8 rounded-lg transition-colors duration-200 shadow-md hover:shadow-lg"
      >
        Click me
      </button>
    </div>
  </div>
</template>
