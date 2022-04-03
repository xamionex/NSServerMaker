<template>
  <div id="app" class="grid grid-cols-2">
    <NavBar />
  </div>
</template>

<script type="text/javascript">
import NavBar from "./components/sidebar/NavBar.vue";
export default {
  components: {
    NavBar, // register component
  },
};
</script>