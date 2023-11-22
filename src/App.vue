<script setup>
import {  RouterView } from 'vue-router'

</script>

<template>
    <div id="nav">
       <Router-Link  to="/">Inicio</Router-Link> |
       <Router-Link  to="/">Brasil</Router-Link> 
       <Router-Link  to="/about">Acerca de</Router-Link>
    </div> 
     <div class="container">
         <RouterView />
      </div>
</template>

<style scoped>

</style>
