<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">

    <PageHeader />
    <PageBody />
    <PageFooter />
  </div>
</template>

<script>

import PageHeader from './components/PageHeader.vue'
import PageFooter from './components/PageFooter.vue'
import PageBody from './components/PageBody.vue'
export default {
  name: 'App',
  components: {

    PageHeader,
    PageBody,
    PageFooter
    
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
