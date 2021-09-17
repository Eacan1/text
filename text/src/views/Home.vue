<!--
 * @Author: your name
 * @Date: 2021-09-17 16:10:06
 * @LastEditTime: 2021-09-17 16:26:39
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \text\src\views\Home.vue
-->
<template>
  <div class="home">
    <Tian />
    <Yang />
  </div>
</template>

<script>
// @ is an alias to /src
import Tian from '../components/Tian.vue';
import Yang from '../components/Yang.vue';
export default {
  name: "Home",
  components: {
    Tian,
    Yang,
  },
};
</script>
