<!-- layout -->
<template>
  <nav>
    <div class="nav__left f-normal uc">
      <ul>
        <li>
          <svg style="margin-top: 4px;" height="20" viewBox="0 0 26 20" width="26"><path d="m0 7.8941524v-5.06424c0-1.25802855 1.24304218-2.82986584 2.79374075-2.82986584h5.00344022l-2.17336935 2.20038597h-2.83007087c-.30811627 0-.61991153.31287757-.61991153.62947987v2.86338844zm7.79722695 12.1058476h-5.00344022c-1.24120267 0-2.79374074-1.2584941-2.79374074-2.830797v-5.0628433l2.17336934 2.1999204v2.8629229c0 .3161367.31225514.630411.6203714.630411h2.83053075zm18.20277305-7.8936868v5.0628432c0 1.2580286-1.2412027 2.830797-2.7946605 2.830797h-5.0016007l2.1719897-2.1999203h2.829611c.3104156 0 .6199115-.31474.6199115-.6308767v-2.8624572zm-7.7963072-12.1063132h5.0016007c1.2412027 0 2.7942006 1.25663177 2.7942006 2.82986584v5.06424l-2.1738292-2.20038597v-2.86385403c0-.3166023-.3099557-.62901427-.6203714-.62901427h-2.829611z" fill="#fff"/></svg>
        </li>
        <!-- <li style="transform: translateY(-4px)">Dashboard</li> -->
        <li style="transform: translateY(-5px)" class="li-active">Photos</li>
        <li style="transform: translateY(-5px)">Documents</li>
        <li style="transform: translateY(-5px)">Reports</li>
        <li style="transform: translateY(-5px)">Brand</li>
      </ul>
    </div>
  </nav>
</template>


<!-- style -->
<style scoped lang="scss">
  @import '../assets/style/mq';
  @import '../assets/style/type';

  nav {
    position: fixed;
    width: 100vw; height: 56px;
    background: var(--gravity);
    color: var(--cloud);
    font-size: 1.3rem;
    letter-spacing: 0.8px;
    display: flex;
    align-items: center;
    z-index: var(--zmax);
  }

  li {
    cursor: pointer;
    opacity: 0.6;
    margin-left: 24px;
    margin-right: 20px;
  }

  .li-active { opacity: 1; }

</style>


<!-- logic -->
<script>
  export default {
    name: 'navigation' ,

    mounted() {

    }
  }
</script>
