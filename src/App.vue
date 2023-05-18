<template>
  <div id="app">
  <pageHeader/>
  <div>
    <navbar/>
  </div>
  </div>
</template>

<script>

import pageHeader from './components/pageHeader.vue';
import navbar from './components/navBar.vue';
export default {
  name: 'App',
  components: {
  pageHeader,
  navbar,
  }
}
</script>

<style>

</style>
