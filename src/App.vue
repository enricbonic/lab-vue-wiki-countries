<template>
  <Navbar />
  <router-view></router-view>
</template>
  
<script setup>
   import Navbar from './components/Navbar.vue'
   import CountriesList from './Views/CountriesList.vue'
   import CountryDetails from './Views/CountryDetails.vue'
   

</script>
  
<style scoped>
  
</style>
