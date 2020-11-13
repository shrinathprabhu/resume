<template>
  <div id="app">
    <app-bar />
    <avatar />
    <div style="position: relative">
      <side-bar />
      <main-bar />
    </div>
  </div>
</template>

<script>
import AppBar from "./components/app-bar.vue";
import Avatar from "./components/avatar.vue";
import SideBar from "./components/side-bar.vue";
import MainBar from "./components/main.vue";
export default {
  name: "App",
  components: { AppBar, Avatar, SideBar, MainBar },
};
</script>

<style>
html,
body {
  background-color: #ededed !important;
  font-family: "Roboto", sans-serif;
  margin: 0;
  padding: 0;
  width: 100%;
}
</style>
