<template>
  <div>
    <h1 class="text-red-500">hello</h1>
    <Nav />
    <router-view/>
  </div>
</template>

<script>
import Nav from './components/Nav.vue';



export default {
  name: 'App',
  components: {
    Nav
  }
}
</script>

<style>
</style>
