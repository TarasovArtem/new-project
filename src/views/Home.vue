<template>
  <div class="home">
    <HomePage/>{{ msg }}
    <home-content>{{ massege }}</home-content>
  </div>
</template>

 <script>
// @ is an alias to /src
import HomePage from '@/components/HomePage.vue';
import HomeContent from '@/components/HomeContent.vue';
export default {
  name: 'home',
  components: {
    HomePage,
    HomeContent,
  },
};
</script>