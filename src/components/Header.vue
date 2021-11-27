<template>
  <div class="">
    <h1>Soy un header..</h1>
    <div id="nav">
        <router-link to="/">Home</router-link> |
        <router-link to="/about">About</router-link>
    
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
  props: {
    
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  color: blue;
}
</style>
