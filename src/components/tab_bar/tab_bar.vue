<template>
  <div class="tab-bar">
    <div class="tab-wrap">
      <p class="tab-home" @click="$router.push('/')">
        <!-- <img src="@/assets/home/tab-ico-home-pre.png" alt> -->
        首页
      </p>
      <p>
        <!-- <img src="@/assets/home/tab-ico-community-nor.png" alt> -->
        社区
      </p>
      <p>
        <!-- <img src="@/assets/home/tab-ico-me-nor.png" alt> -->
        我的
      </p>
    </div>
  </div>
</template>

<script>
// import { Component, Vue } from "vue-property-decorator";

export default {
  name: 'tabBar',
  data() {
    return {
      path: this.$route.path
    };
  },
  created() {
  }
}
</script>

<style lang="scss" scoped>
.tab-bar {
  position: fixed;
  left: 0;
  bottom: 0;
  width: 100%;
  height: 1rem;
  line-height: 1rem;
  font-size: 0.24rem;
  background-color: #fff;
  box-shadow: 0 -2px 6px 0 rgba(0,0,0,.1);
  // img {
  //   width: 0.28rem;
  // }
  .tab-wrap {
    display: flex;
    p {
      flex: 1;
    }
    img {
      width: 0.56rem;
    }
    .tab-home {
      
    }
  }
}
</style>

