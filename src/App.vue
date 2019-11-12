<template>
  <div id="app">
    <Truth/>
    <TabContainer/>
  </div>
</template>

<script>
import TabContainer from './components/TabContainer'

export default {
  name: 'App',
  components: {
    TabContainer
  }
}
</script>

<style>
* {
  padding: 0;
  margin: 0;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

}
</style>
