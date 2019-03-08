<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <TabBar></TabBar>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import TabBar from '@/components/tab_bar/tab_bar.vue';

export default {
  name: 'home',
  components: {
    TabBar
    // HelloWorld
  }
}
</script>
