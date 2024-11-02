<script setup>
import Forms from './components/forms.vue' 
</script>

<template>
  <div id="container"> 
    <div>
    Create your account 
    </div>
    <div>
      email: <input type="text" v-model="email">
    </div>
    <div>
      password: <input type="password" v-model="password">
    </div>
    <div> 
      confirm your passowrd: <input type="password" v-model="confirmPassword">
    </div> 
  </div>
</template>
