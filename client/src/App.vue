<script setup>
import { ref } from "vue"
  const cinter = ref(0)

  function increment() {
    cinter.value++
  }

  // onMounted(()=> {console.log(cinter);})
  
</script>
<!-- http://localhost:5173/ -->
<script>
</script>

<template>
  <h1>Мы пьём пиво и работаем с Vue.js</h1>
  <button @click = "increment">Счётчик yes: {{ cinter }}</button>
</template>