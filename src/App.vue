<template>
  <amplify-authenticator id="app">
    <div>Header</div>
    <amplify-greetings></amplify-greetings>
    <my-map />
  </amplify-authenticator>
</template>

<script>
import MyMap from './components/MyMap.vue'

export default {
  name: 'App',
  components: {
    'my-map': MyMap
  }
}
</script>

<style>
body {
  padding: 0;
  margin: 0;
}
#app {
  height: 100vh;
}
</style>
