<template>
  <div class="tab-container">
    <Tab  v-for="tab in tabs" :key="tab.id" :title="tab.title" ></Tab>
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
      title: 'title',
      tabs: [
        { title: 'Saved' },
        { title: 'Stops' },
        { title: 'Search' }
      ]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.tab-container { display: flex; }
</style>
