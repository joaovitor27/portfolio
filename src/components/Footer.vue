<template>
  <footer class="footer color-footer">
    <div class="section-heading-footer">
      <p>
        <strong style="color: white">João Vitor | Copyright ©2023 Todos os direitos reservados.</strong>
      </p>
    </div>
  </footer>
</template>

<script lang="ts">
import {defineComponent} from 'vue';

export default defineComponent({
  name: 'FooterBar',
  components: {}
});
</script>

<style scoped>
.color-footer {
  background-color: #021154;
}
.section-heading-footer {
    text-align: center;
    margin-top: 6em;
    margin-bottom: 6em;
}
.footer {
    padding: 3rem 1.5rem 3rem;
}
</style>
