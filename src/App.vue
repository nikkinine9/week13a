<template>
  <div id="app">
    <layout-header sitename="Fullstack Development 2020"></layout-header>
    <layout-main></layout-main>
    <layout-footer></layout-footer>
  </div>
</template>

<script>
import LayoutHeader from './components/LayoutHeader.vue'
import LayoutMain from './components/LayoutMain.vue'
import LayoutFooter from './components/LayoutFooter.vue'

export default {
  name: 'App',
  components: {
    LayoutHeader,
    LayoutMain,
    LayoutFooter
  },
}
</script>

<style>
* {
  padding: 0rem;
  margin: 0rem;
  font-family: 'Courier New', Courier, monospace;
}
#app {
  display: grid;
  grid-template-rows: auto 1fr auto;
  min-height: 100vh;
}
</style>
