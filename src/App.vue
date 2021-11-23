<template>
  <div>
    <Header />
    <Main />
    <footer>Footer</footer>
  </div>
</template>

<script>
import Header from "./components/header.vue"
import Main from "./components/main.vue"

export default {
  name: 'App',
  components: {
    Header,
    Main
  }
}
</script>

<style lang="scss">
  body{
    font-family: Arial, Helvetica, sans-serif;
  }
  h1{
    text-align: center;
  }
</style>
