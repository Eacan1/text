<!--
 * @Author: your name
 * @Date: 2021-09-17 16:10:06
 * @LastEditTime: 2021-09-17 16:24:52
 * @LastEditors: your name
 * @Description: In User Settings Edit
 * @FilePath: \text\src\App.vue
-->
<template>
  <div id="app">
    <div id="nav">
    </div>
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
