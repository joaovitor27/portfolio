<template>
  <section class="section" id="portfolio">
    <div class="container">
      <div class="section-heading">
        <h3 class="title is-2">Portfólio</h3>
        <h4 class="subtitle is-5">Meus últimos trabalhos</h4>
      </div>
      <MyProjetos></MyProjetos>
    </div>
  </section>
</template>

<script lang="ts">
import {defineComponent} from 'vue';
import MyProjetos from "@/components/SectionPortfolio/MyProjetos.vue";

export default defineComponent({
  name: 'SectionPortfolio',
  components: {MyProjetos}
});
</script>

<style scoped>

</style>
