<template>
<div class="container">
  <Title title="Word &amp; Simple" />
  <Navbar />
  <Article />
</div>
</template>

<script>
import Title from './components/Title.vue'
import Navbar from './components/Navbar.vue'
import Article from './components/Article.vue'


export default {
  name: 'App',
  components: {
    Title,
    Navbar,
    Article
  }
}
</script>

<style>
#app {
  font-family: 'Roboto', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
