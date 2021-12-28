<template>
  <div id="app">
    <h1>黑马头条</h1>
    <!-- 路由的出口 -->
    <router-view />
  </div>
</template>

<script>
export default {
  name: 'APP',
  methods: {
    fn () {
      const a = 'asjksdh'
      console.log(a)
    }
  }
}
</script>

<style lang="less"></style>
