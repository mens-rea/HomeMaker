<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})

const count = ref(0)
</script>

<template>
  <div class="row">
    <h1 class="text-xl font-bold mt-3">HomeMaker</h1>
    <p>Household management should be fun...</p>
  </div>

  <div class="md:container">
    <div class="grid grid-cols-5 gap-4 mt-5 mx-auto">
      <div class="max-w-xs rounded overflow-hidden shadow-lg">
        <img class="w-full" src="https://picsum.photos/250/100" alt="Sunset in the mountains">
        <div class="px-6 py-4">
          <div class="font-bold text-xl mb-2">The Coldest Sunset</div>
          <p class="text-gray-700 text-xs">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
          </p>
        </div>
      </div>

      <div class="max-w-xs rounded overflow-hidden shadow-lg">
        <img class="w-full" src="https://picsum.photos/250/100" alt="Sunset in the mountains">
        <div class="px-6 py-4">
          <div class="font-bold text-xl mb-2">The Coldest Sunset</div>
          <p class="text-gray-700 text-xs">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
          </p>
        </div>
      </div>

      <div class="max-w-xs rounded overflow-hidden shadow-lg">
        <img class="w-full" src="https://picsum.photos/250/100" alt="Sunset in the mountains">
        <div class="px-6 py-4">
          <div class="font-bold text-xl mb-2">The Coldest Sunset</div>
          <p class="text-gray-700 text-xs">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
          </p>
        </div>
      </div>

      <div class="max-w-xs rounded overflow-hidden shadow-lg">
        <img class="w-full" src="https://picsum.photos/250/100" alt="Sunset in the mountains">
        <div class="px-6 py-4">
          <div class="font-bold text-xl mb-2">The Coldest Sunset</div>
          <p class="text-gray-700 text-xs">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
          </p>
        </div>
      </div>

      <div class="max-w-xs rounded overflow-hidden shadow-lg">
        <img class="w-full" src="https://picsum.photos/250/100" alt="Sunset in the mountains">
        <div class="px-6 py-4">
          <div class="font-bold text-xl mb-2">The Coldest Sunset</div>
          <p class="text-gray-700 text-xs">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
  /* Place your custom css here */
</style>
