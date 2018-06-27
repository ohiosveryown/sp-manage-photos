<!-- layout -->
<template>
  <div id="galleries">
    <!-- <h1>App Logic</h1> -->
    <navigation/>
    <router-view/>
  </div>
</template>


<!-- style -->
<style lang="scss">
  @import './assets/style/mq';

</style>


<!-- logic -->
<script>
  import navigation from '@/components/Navigation.vue'

  export default {
    components: { navigation },
  }
</script>
