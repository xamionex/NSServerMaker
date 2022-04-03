<template>
  <div id="app">
    <Navbar />
    <router-view></router-view>
  </div>
</template>

<script type="text/javascript">
import Navbar from "./components/sidebar/Navbar.vue";
import Home from "./components/Home.vue"
export default {
  components: {
    Navbar,
    Home,
  },
};
</script>