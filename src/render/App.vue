<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
   <div class="common-layout">
    <el-container>
      <el-aside class="side" width="200px">Aside</el-aside>
      <el-main class="main">
        <HelloWorld msg="Vite + Vue" />
      </el-main>
    </el-container>
  </div>

</template>

<style lang="scss" scoped>
 .common-layout{
  height: 100vh;
  .side{
    background:   #d9ecff;
    height: 100vh;
  }
  .main{
    background-color:  #ecf5ff;
  }
 }
</style>
