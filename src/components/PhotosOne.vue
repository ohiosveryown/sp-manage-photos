<!-- layout -->
<template>
  <div class="wrap">



  </div>
</template>


<!-- style -->
<style scoped lang="scss">
  @import '../assets/style/mq';
  @import '../assets/style/type';

  .wrap {
    padding: 72px 24px 0 32px;
    min-width: 100%;
    width: 60vw;
  }

  header {
    position: sticky;
    top: 0;
    z-index: var(--z4);
    padding-bottom: 16px;
    width: 100%;
  }

  .actions {
    position: relative;
    margin-top: 4.4px;
  }

  .actions, .album-actions, .sorting, .tools, .album-meta {
    display: flex;
    justify-content: flex-end;
  }

  .sorting { margin-right: auto; }

</style>


<!-- logic -->
<script>
  export default {
    name: 'photosOne' ,

    mounted() {

    }
  }
</script>
