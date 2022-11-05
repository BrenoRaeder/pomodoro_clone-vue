<template>
  <Nav></Nav>
  <router-view/>
</template>

<script>
import Nav from './components/Nav.vue'

export default {
  components: {
    Nav,
  }
}
</script>

<style>
body {
  background: #ca5652;
  margin: 0;
  padding: 0;
  color: #fff;
  font-family: Arial, Helvetica, sans-serif;
}
</style>
