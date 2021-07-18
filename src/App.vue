<template>
  <div id="app">
    <div class="nav">
      <Nav />
    </div>
    <router-view />
    <div>
      <Footer />
    </div>
  </div>
</template>

<script>
import Nav from './components/nav'
import Footer from './components/footer'

export default {
  name: 'App',
  components: {
    Nav,
    Footer
  }
}
</script>

<style>

</style>
