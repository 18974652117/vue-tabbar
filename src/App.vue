<template>
  <div id="app">
    <main-tab-bar></main-tab-bar>

    <router-view/>
  </div>
</template>

<script>
import mainTabbar from "./components/mainTabbar/mainTabbar.vue"
export default {
  name:"APP",
  components: {
    "main-tab-bar": mainTabbar,
  }
}
</script>

<style>
@import "./assets/css/base.css";

</style>
