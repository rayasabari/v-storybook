<template>
  <Header />
  <div style="margin-top: 40px;">
    <Button label="Get Started" :primary="true" />
  </div>
  <div style="margin-top: 10px;">
    <Button label="Learn More" size="small" />
  </div>
  <HelloWorld msg="Welcome to Your Vue.js App" />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Button from './stories/Button.vue'
import Header from './stories/Header.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Button,
    Header
  }
}
</script>

<style>
body {
  margin: auto;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
