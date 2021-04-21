<!--
 * @Author: your name
 * @Date: 2021-04-21 14:04:35
 * @LastEditTime: 2021-04-21 14:40:13
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: /my-blog/src/components/SiteHeader.vue
-->
<template>
   <header>
      <div class="bg-gray-900 p-4 mt-0 w-full">
         <div class="container mx-auto flex items-center">
            <div class="flex text-white font-extrabold">
               <g-link to="/" class="flex text-white text-base no-underline hover:text-white hover:no-underline">
                  </g-link>
            </div>
         </div>
      </div>
   </header>
</template>

<script>

    export default {
        name: "SiteHeader",
    }
</script>

<style scoped>

</style>