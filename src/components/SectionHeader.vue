<template>
  <section class="hero is-fullheight is-fullheight-with-navbar degrade">
    <div class="hero-body">
      <div class="container">Olá! Eu sou
        <h1 class="title is-1 color-white">
          João Vitor da Silva Monteiro
        </h1>
        <div class="typing-effect color-white">
          <p class="subtitle is-3 color-white">
            <strong class="color-white">Desenvolvedor <br> Full Stack</strong>
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import {defineComponent} from 'vue';

export default defineComponent({
  name: 'SectionHeader',
  components: {}
});
</script>

<style scoped>
.color-white {
  color: white;
}

.typing-effect p {
  overflow: hidden;
  border-right: .15em rgba(255, 255, 255, 0.85); /* Simula o cursor de digitação */
  white-space: nowrap; /* Evita quebrar a linha */
  margin: 0;
  padding: 0;
  animation: typing 3s steps(40) 1 alternate;
}

@keyframes typing {
  from {
    width: 0;
  }
  to {
    width: 100%;
  }
}
</style>
