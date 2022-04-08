<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Hello Vue 3.0 + Vite" />
  <F>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import F from './components/f.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    F,
  }
}
</script>
