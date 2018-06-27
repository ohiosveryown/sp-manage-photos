<!-- layout -->
<template>
  <section class="debug galleries">
    <h3 class="f-lg f-bold">Galleries Component</h3>
  </section>
</template>


<!-- style -->
<style scoped lang="scss">
  @import '../assets/style/mq';
  @import '../assets/style/type';

  section {
    @include breakpoint(mdl) {
      max-width: 25vw;
    }
  }
</style>


<!-- logic -->
<script>
  export default { name: 'Galleries' }
</script>
