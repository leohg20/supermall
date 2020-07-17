<template>
  <div id="app">
    <tabBar>
      <tabBarItem>
        img
      </tabBarItem>
      <tabBarItem></tabBarItem>
      <tabBarItem></tabBarItem>
    </tabBar>
  </div>
</template>
<script>
  const tabBar = require('@/components/tabBar/tabBar')
  const tabBarItem = require('@/components/tabBar/tabBarItem')
  export default {
    name: "App",
    components: {
      tabBar,
      tabBarItem
    }
  }
</script>
<style>

</style>
