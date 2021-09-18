<template>
  <div id="app">
    <!--<img alt="Vue logo" src="./assets/logo.png">-->
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>

  <!--
  <div class="text-center my-3">
    <b-button v-b-popover.hover.top="'I am popover directive content!'" title="Popover Title">
      Hover Me
    </b-button>

    <b-button id="popover-target-1">
      Hover Me
    </b-button>
    <b-popover target="popover-target-1" triggers="hover" placement="top">
      <template #title>Popover Title</template>
      I am popover <b>component</b> content!
    </b-popover>
  </div>
  -->

</template>

<script>
import HelloWorld from './components/popover.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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
