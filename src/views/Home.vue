<!-- layout -->
<template>
  <div id="galleries">
    <Galleries/>
    <!-- <albums/> -->
    <album/>
  </div>
</template>


<!-- style -->
<style lang="scss" scoped>
  @import '../assets/style/mq';

  #galleries {
    display: flex;
  }

</style>


<!-- logic -->
<script>
  import Galleries from '@/components/Galleries.vue'
  import albums from '@/components/Albums.vue'
  import album from '@/components/Album.vue'

  export default {
    components: { Galleries, albums, album },
  }
</script>
