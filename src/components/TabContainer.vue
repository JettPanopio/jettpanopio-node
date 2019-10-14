<template>
  <div class="tab-container">
    <p>{{msg}}</p>
    <Tab  v-for="tab in tabs" :key="tab.id" >
      
    </Tab>
  </div>
</template>

<script>
import Tab from '../components/Tab'

export default {
  name: 'TabContainer',
  components: {
    Tab
  },
  data () {
    return {
      msg: 'This is tab-container',
      tabs: [
        { title: 'Saved Tab' },
        { title: 'Stops Tab' },
        { title: 'Search Tab' }
      ]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
