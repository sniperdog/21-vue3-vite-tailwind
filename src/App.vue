<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
  <ChitChat />
  <br>
  <MessageMe />
  <br>
  <HelloWorld msg="Hello Vue 3 + TypeScript + Vite" />
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import HelloWorld from './components/HelloWorld.vue'
import ChitChat from './components/ChitChat.vue'
import MessageMe from './components/MessageMe.vue'

export default defineComponent({
  name: 'App',
  components: {
    HelloWorld,
    ChitChat,
    MessageMe
  }
})
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  img: center
}
</style>
