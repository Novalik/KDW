<template>

  <Nav />
  
  <div class="cards p-5 flex justify-center flex-wrap">
    <Card v-for="item in 6" />
  </div>

</template>

<script>
import Nav from '../components/Nav.vue'
import Card from '../components/Card.vue'

export default {
  name: 'Index',
  components: {
    Nav,
    Card
  }
}
</script>

<style>
</style>
