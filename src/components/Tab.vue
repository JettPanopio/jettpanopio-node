<template>
  <div class="tab">
    <p>{{title}}</p>
  </div>
</template>

<script>
export default {
  name: 'Tab',
  props:['title']
}
</script>

<style scoped>
.tab { height: 100vh; width: calc( 100% / 3 ); }
.tab > p { text-align: center; }
</style>
