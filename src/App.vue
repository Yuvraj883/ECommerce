<template>
 
  <ul class="nav nav-tabs justify-content-end">
  <li class="nav-item">
  <router-link to="/" class="nav-link active">Home</router-link>
  </li>
  <li class="nav-item">
    <router-link class="nav-link" to="/about">About
  </router-link></li>
  <li class="nav-item">
    <router-link class="nav-link" to="#">Link</router-link>
  </li>
  <li class="nav-item">
    <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a>
  </li>
</ul>
  
  <router-view/>
</template>

<style lang="scss">

</style>
