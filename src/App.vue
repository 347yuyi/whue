<template>
  <div id="app">
    <img src="./assets/test1.jpg" style="width: 200px;height:200px">
    <div>
      <el-button @click="startHacking">开始测试</el-button>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    startHacking () {
      this.$notify({
        title: '成功！',
        type: 'success',
        message: '开始了',
        duration: 5000
      })
    }
  }
}
</script>

<style>
#app {
  font-family: Helvetica, sans-serif;
  text-align: center;
}
</style>
