<template>
  
  <div class="container">
    <header-global></header-global>  
    <router-view/>
    <footer>
        <footer-content>{{ msg }}</footer-content>
    </footer>
  </div>
</template>

<script>
import headerGlobal from '@/components/headerGlobal.vue';
import footerContent from '@/components/footerContent.vue';

export default {
  name: 'app',
  components: {
    headerGlobal,
    footerContent,
  },
};
</script>


<style lang="scss">
* {
  padding: 0;
  margin: 0;
}

.container {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-color: #4f4d63;
  height: 80px;
  padding: 0;
}

.nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #fff;
    margin-left: 10px;
    text-decoration: none;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
.logoHead {
  //width: 150px;
  height: 50px;
  margin-top: 15px;
  margin-left: 65px;
}
</style>
