<script setup>
const handleClick = () => {
  alert('Hello from Vue!')
}
</script>

<template>
  <div class="min-h-screen bg-gradient-to-br from-blue-50 to-indigo-100 flex items-center justify-center p-4">
    <div class="bg-white rounded-2xl shadow-xl p-8 max-w-md w-full text-center">
      <h1 class="text-4xl font-bold text-pink-300 mb-6">
        Hello World 💣
      </h1>
      <button
        @click="handleClick"
        class="bg-gradient-to-b from-gray-300 via-gray-400 to-gray-500 hover:from-gray-400 hover:via-gray-500 hover:to-gray-600 text-gray-800 font-bold py-3 px-8 rounded-lg transition-all duration-200 shadow-lg hover:shadow-xl border border-gray-400"
      >
        Click me
      </button>
    </div>
  </div>
</template>
