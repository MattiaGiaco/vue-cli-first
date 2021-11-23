<template>
  <div>
    <Header />
    <Main />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/header.vue"
import Main from "./components/main.vue"
import Footer from "./components/footer.vue"

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer
  }
}
</script>

<style>
  body{
    font-family: Arial, Helvetica, sans-serif;
  }
  h1{
    text-align: center;
    color: crimson;
  }
</style>
