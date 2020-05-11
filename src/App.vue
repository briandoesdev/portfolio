<template>
  <div id="app">
    <Navbar />

    <div id="content">
      <Home/>
    </div>

    <Footer />
  </div>
</template>

<script>
import Home from './components/Home'
import Navbar from './components/Navbar'
import Footer from './components/Footer'

export default {
  name: 'App',
  components: {
    Navbar,
    Home,
    Footer
  }
}
</script>

<style>
#content {
  text-align: left;
  color: #2c3e50;
}
</style>
