<!-- layout -->
<template>
  <div id="galleries">
    <h2>Hello (Home) World</h2>
    <Galleries/>
  </div>
</template>


<!-- style -->
<style lang="scss" scoped>
  @import '../assets/style/mq';

</style>


<!-- logic -->
<script>
  import Galleries from '@/components/Galleries.vue'

  export default {
    components: { Galleries },
  }
</script>
