<template>
  <div>
    <h1>main</h1>
    <el-container>
      <el-aside width="200px">Aside</el-aside>
      <el-container>
        <el-header>Header</el-header>
        <el-main>Main</el-main>
      </el-container>
    </el-container>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: "Main"
}
</script>

<style scoped>

</style>