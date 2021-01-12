<script>
// @ is an alias to /src
import HeaderBar from "@/components/HeaderBar.vue";
import SideBar from "@/components/SideBar.vue";


export default {
  name: "Home",
  components: {
    HeaderBar, SideBar
  }
};
</script>

<template>
  <div class="home">
    <header-bar></header-bar>
    <side-bar></side-bar>
  </div>
</template>

