<template>
  <nav class="navbar degrade is-fixed-top">
    <div class="navbar-brand">
      <div class="navbar-burger burger" data-target="navbarExampleTransparentExample">
        <span></span>
        <span></span>
        <span></span>
      </div>
    </div>
    <LinkNavBar></LinkNavBar>
  </nav>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import LinkNavBar from "@/components/NavBar/LinkNavBar.vue";
export default defineComponent({
  name: 'NavBar',
  components: {
    LinkNavBar
  }
});
</script>

<style scoped>

</style>
