<template>
  <div class="text-center my-3">
    test
    <img alt="Vue logo" src="./assets/logo.png">
    <!--
    <b-button v-b-popover.hover.top="'I am popover directive content!'" title="Popover Title">
      Hover Me
    </b-button>
    -->

    <b-button id="popover-target-1">
      Hover Me
    </b-button>
    <b-popover target="popover-target-1" triggers="hover" placement="top">
      <template #title>Popover Title</template>
      I am popover <b>component</b> content!
    </b-popover>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
