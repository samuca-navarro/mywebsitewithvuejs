<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Menu from '@/components/Menu.vue';
</script> 

<template>
  <header>
    <div class="main-container">
      <div class="container-one">
        <Menu/>
      </div>
      <br>
    </div> 
  </header>
  <RouterView />
</template>

<style>

/* .wrapper {
  margin: 5%;
  width: 90%;
  padding: 10px;
} */

</style>
