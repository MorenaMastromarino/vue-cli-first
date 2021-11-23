<template>
  <div>
    <Title />
    <Main/>
    <Footer />

  </div>
</template>

<script>
import Title from './components/Title.vue';
import Main from './components/Main.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    Title,
    Main,
    Footer
  }
}
</script>

<style>
.container {
  width: 70%;
  margin: 0 auto;
}
</style>
