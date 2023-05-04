<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <div class="logo-nav">
      

    

      <nav>
        <RouterLink to="/"></RouterLink>
       
      </nav>
    </div>
    
  </header>
  <RouterView />
</template>

<style scoped>
*{
  text-decoration: none;
  color: black;
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

nav {
  display: flex;
  justify-content: end;
  align-items: center;
  gap: 20px;
  text-decoration: none;
  margin-top: 40px;
  margin-right: 100px;
  
 
}


</style>
