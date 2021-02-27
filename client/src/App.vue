<template>
  <div id="app">
    <Nav />


      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    
    <router-view/>
  </div>
</template>

<script>
  import Nav from "./components/Nav";
export default {
  components: {
    Nav
  }
}
</script>

<style lang="scss">

  @import url('https://fonts.googleapis.com/css2?family=Ranchers&display=swap');


</style>
