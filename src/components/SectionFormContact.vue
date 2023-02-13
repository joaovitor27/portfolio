<template>
  <section class="section" id="contact">
    <div class="container">
      <div class="section-heading">
        <h3 class="title is-2">Contato</h3>
        <h4 class="subtitle is-5">Envie sua mensagem</h4>
      </div>
      <FormContact></FormContact>
    </div>
  </section>
</template>

<script lang="ts">
import {defineComponent} from 'vue';
import FormContact from "@/components/SectionFormContact/FormContact.vue";

export default defineComponent({
  name: 'SectionFormContact',
  components: {FormContact}
});
</script>

<style scoped>

</style>
