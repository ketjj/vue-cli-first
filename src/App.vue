<template>
  <div id="app">
    <MyHeader />      

    <MyJumboton />

  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue';
import MyJumboton from './components/MyJumbotron.vue'


export default {
  name: 'App',
  components: {
    MyHeader,
    MyJumboton
  }
}
</script>

<style lang="scss">

</style>
