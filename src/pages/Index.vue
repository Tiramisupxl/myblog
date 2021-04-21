<!--
 * @Author: your name
 * @Date: 2021-04-20 17:50:22
 * @LastEditTime: 2021-04-21 14:38:44
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: /my-blog/src/pages/Index.vue
-->
<template>
  <Layout>

    <!-- Learn how to use images here: https://gridsome.org/docs/images -->
    <g-image alt="Example image" src="~/favicon.png" width="135" />

    <h1>Hello, world!</h1>

    <!-- <p v-for="edge in $page.posts.edges" :key="edge.node.id">
      <a :href="edge.node.path">{{edge.node.title}}</a>
    </p> -->

  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Hello, world!'
  }
}
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
</style>
