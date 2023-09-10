<template>
  <div class="column is-2" style="  display: flex;
  justify-content: center; /* Centraliza horizontalmente */
  align-items: center;">
    <div class="card" style="  display: flex;
  justify-content: center; /* Centraliza horizontalmente */
  align-items: center; position: relative">
      <div class="card-my">
        <div class="my-image">
          <figure class="image">
            <img src="../../../public/img/foto-profile.jpg" alt="Placeholder image">
          </figure>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import {defineComponent} from 'vue';

export default defineComponent({
  name: 'MyImagemFullStack',
  components: {}
});
</script>

<style scoped>
.card-my {
  width: 400px; /* Largura desejada para o card */
  height: 325px; /* Altura desejada para o card (pode ser ajustada conforme necessário) */
  overflow: hidden;
  display: flex;
  justify-content: center; /* Centraliza horizontalmente */
  align-items: center;
}

.my-image {
  width: 400px; /* Largura desejada para o card */
  height: 350px; /* Altura desejada para o card (pode ser ajustada conforme necessário) */
  overflow: hidden;
}

.card-my img {
  width: 100%;
  height: auto;
  display: flex;
}
</style>
