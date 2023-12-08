<script setup>
import { ref } from 'vue'
// ref用于定义响应式数据
const count = ref(0)
</script>



<template>
  <main>
    <div>
      <h4>the current count is...</h4>
      <h1>{{ count }}</h1>
      <button @click="count--">-</button>
      <button @click="count++">+</button>
    </div>
  </main>
</template>



<style scoped>
main {
  background-color: aliceblue;
  width: 100vw;
  height: 100vh;
  justify-content: center;
  display: flex;

  align-items: center;
}

div {
  text-align: center;
}
</style>
