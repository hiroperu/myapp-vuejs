<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="HAHAHAHAH!!!!!!!"/>
  <EventHandling/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import EventHandling from './components/EventHandling.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    EventHandling
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
