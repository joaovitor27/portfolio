<template>
  <div id="navbarExampleTransparentExample" class="navbar-menu">
    <div class="navbar-end">
      <a class="navbar-item color-white" href="#about">
          <span class="icon">
            <i class="fas fa-info"></i>
          </span>
        <span>Sobre mim</span>
      </a>
      <a class="navbar-item color-white" href="#services">
          <span class="icon">
            <i class="fas fa-bars"></i>
          </span>
        <span>Serviços</span>
      </a>
      <a class="navbar-item color-white" href="#portfolio">
          <span class="icon">
            <i class="fas fa-th-list"></i>
          </span>
        <span>Trabalhos</span>
      </a>
<!--      <a class="navbar-item color-white" href="#contact">-->
<!--          <span class="icon">-->
<!--            <i class="fas fa-envelope"></i>-->
<!--          </span>-->
<!--        <span>Contato</span>-->
<!--      </a>-->
      <a class="navbar-item color-white" href="#resume">
          <span class="icon">
            <i class="fas fa-file-alt"></i>
          </span>
        <span>Resumo</span>
      </a>
    </div>
  </div>
</template>

<script lang="ts">
import {defineComponent} from 'vue';

export default defineComponent({
  name: 'LinkNavBar',
  components: {}
});
</script>

<style scoped>
  .color-white {
    color: white;
  }
  a:hover {
    background-color: #041f96;
    color: white;
  }
</style>
