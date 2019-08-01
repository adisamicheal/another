<template>
  <div id="app">
      <Sidebar />
      <Navbar />
    <router-view/>
  </div>
</template>

<script>
  import Sidebar from '@/components/Sidebar.vue'
  import Navbar from '@/components/Navbar.vue'
  

  export default {
    name: 'app',
    components: {
      Sidebar,
      Navbar,
    }
  } 
</script>

<style>

</style>
