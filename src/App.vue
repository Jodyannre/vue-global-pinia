<template>
    <h3>{{ store.counter }} x 2 = {{ store.times2 }}</h3>
    <button @click="store.increment(1)">Increment</button>

</template>
  
<script lang="ts" setup>
  import { useCounterStore } from '@/store/counter'
  const store = useCounterStore()

</script>
  
<style scoped>
</style>
  