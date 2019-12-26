<template>
  <div id="app">
    <router-view />
    <main-tab-bar />
  </div>
</template>

<script>
import MainTabBar from "./components/content/mainTabBar/MainTabBar";
export default {
  name: 'app',
  components: {
    MainTabBar
  }
}
</script>

<style>
  body {
    padding: 3px;
    margin: 0;
  }
</style>
