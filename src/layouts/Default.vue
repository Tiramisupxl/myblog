<!--
 * @Author: your name
 * @Date: 2021-04-20 17:50:22
 * @LastEditTime: 2021-04-21 14:37:19
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: /my-blog/src/layouts/Default.vue
-->
<template>
  <div>
      <site-header class="mb-5"/>
      <div class="mt-5 p-5">
        <slot />
      </div>
  </div>
</template>


<script>
  import SiteHeader from "../components/SiteHeader.vue";
  export default {
    components: {SiteHeader}
  }
</script>

<style scoped>
/* @import url(../assets/style/main.css); */
</style>