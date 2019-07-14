<template>
  <div id="app">
    <!-- 一级路由对应组件渲染的位置 -->
    <router-view></router-view>

  </div>
</template>

<script>
export default {
  render () {
    return (
      <Breadcrumb separator="/">
        <Breadcrumb.Item>首页</Breadcrumb.Item>
        <Breadcrumb.Item>活动管理</Breadcrumb.Item>
        <Breadcrumb.Item>活动列表</Breadcrumb.Item>
        <Breadcrumb.Item>活动详情</Breadcrumb.Item>
        <Breadcrumb.Item>活动详情</Breadcrumb.Item>
        <Breadcrumb.Item>活动详情</Breadcrumb.Item>
      </Breadcrumb>
    )
  }
}
</script>

<style lang="less">
</style>
