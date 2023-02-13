<template>
  <section class="section" id="services">
    <div class="section-heading">
      <h3 class="title is-2">Serviços</h3>
      <h4 class="subtitle is-5">Procura algum serviço?</h4>
    </div>
    <MyServices></MyServices>
  </section>
</template>

<script lang="ts">
import {defineComponent} from 'vue';
import MyServices from "@/components/SectionServices/MyServices.vue";

export default defineComponent({
  name: 'SectionServices',
  components: {MyServices}
});
</script>

<style scoped>

</style>
