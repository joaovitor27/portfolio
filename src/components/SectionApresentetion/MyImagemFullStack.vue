<template>
  <div class="column is-2">
    <div class="card" style="  display: flex;
  justify-content: center; /* Centraliza horizontalmente */
  align-items: center; position: relative; border-radius: 50%; border: #041f96 solid 5px; width: 400px; height: 350px; overflow: hidden;"
    >
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
  border-radius: 50%;
}

.my-image {
  width: 400px; /* Largura desejada para o card */
  height: 350px; /* Altura desejada para o card (pode ser ajustada conforme necessário) */
  overflow: hidden;
  border-radius: 50%;
}

.card-my img {
  width: 100%;
  height: auto;
  display: flex;
}
</style>
