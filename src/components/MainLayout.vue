<script setup>
import MainScore from '@/components/MainScore.vue'

</script>

<template>
  <main>
    <div class="card">
      <RouterView />      
    </div>

  </main>
  <MainScore />
</template>

<style lang="postcss" scoped>
  main {
    @apply flex justify-center items-center h-screen bg-gradient-to-r from-cyan-200 via-cyan-600 to-blue-800;
    & .card {
      @apply flex h-5/6 min-h-fit w-11/12 flex-col items-center gap-16 overflow-auto rounded-lg bg-gradient-to-r from-orange-100 via-orange-300 to-orange-500 shadow-lg;
    }
  }

 
</style>
