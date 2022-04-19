<template lang='pug'>
  div#app
    Product(productName="Socks", productImage="./assets//green-socks.png")
  
</template>

<script>

// import HelloWorld from './components/HelloWorld.vue'
import Product from './components/Product.vue'
export default {
  name: 'App',
  components: {
    Product
  }
}
</script>

<style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    background-color: azure;
  }
</style>
