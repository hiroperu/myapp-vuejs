<template>
  <div id="event-handling">
    <h1>{{ message }}</h1>
    <button v-on:click="reverseMessage">Reverse Message</button>
  </div>
</template>

<script>
export default {
    name: 'EventHandling',
    data(){
        return {
            message: 'Hello Vue.js!'
        }
    },
    methods: {
        reverseMessage() {
           this.message = this.message
                              .split('')
                              .reverse()
                              .join('')
        }
    }
}
</script>

const EventHandling = {
  data() {
    return {
      message: 'Hello Vue.js!'
    }
  },
  methods: {
    reverseMessage() {
      this.message = this.message
        .split('')
        .reverse()
        .join('')
    }
  }
}