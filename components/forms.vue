<script setup>
import { ref } from 'vue'

const count = ref(0)
</script>

<template>
  <button @click="count++">You clicked me {{ count }} times.</button>
</template>
<style>
  button{
    background: red;
    padding : 10px 40px 30px 50px;
  }
</style>
