<template>
  <div id="app">
   
      <message>Hello There</message>
      <message>Number 2</message>
      <message>Number 2</message>
      <message>Number 2</message>
      <message>Number 2</message>
      <message>Number 2</message>

      <counter></counter>



  </div>
</template>

<script>

import Message from './components/Message.vue'
import Counter from './components/Counter.vue'

export default {
  name: 'app',

  components: {Message, Counter},
  // components: {Counter},

  data () {
    return {
     
    }
  }
}
</script>

<style>






</style>
