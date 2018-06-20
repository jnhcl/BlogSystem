<style scpoed>
  .home-page{
    display: flex;
    flex-direction: column;
    height: auto;
  }
</style>

<template>
  <div class="home-page">
    <top-menu/>
    <sub-menu/>
  </div>
</template>

<script>
import topMenu from '@/common/head.vue'
import subMenu from '@/common/sub.vue'
export default {
  name: 'HomePage',
  data () {
    return {
      msg: 'Hello CatBlog'
    }
  },
  components: {
    topMenu,
    subMenu
  }
}
</script>
