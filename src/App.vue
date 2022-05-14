<template>
  <Header />
  <Home />
</template>

<script>
import Header from './components/Sections/Header.vue'
import Home from './components/Pages/Home.vue'

export default {
  name: 'App',
  components: {
    Header,
    Home,
  }
}
</script>

<style>

</style>
