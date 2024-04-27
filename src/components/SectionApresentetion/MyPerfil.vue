<template>
  <div class="column">
    <div class="card">
      <div class="card-content skills-content">
        <h3 class="title is-4">Perfil</h3>
        <div class="content">
          <p><b style="padding-right: 2px">Endereço: </b>Rua Quinze, Nº 5628, Santa Maria</p>
          <p><b style="padding-right: 2px">Telefone: </b>(86) 9 9588-0950</p>
          <p><b style="padding-right: 2px">Email: </b>joaovitor.monteiro.188@gmail.com</p>
        </div>
        <br>
        <div class="buttons has-addons is-centered">
          <a href="https://github.com/joaovitor27" class="button button-color-default">Github</a>
          <a href="https://www.linkedin.com/in/jo%C3%A3o-vitor-monteiro-577a49196/"
             class="button button-color-default">LinkedIn</a>
          <a href="https://twitter.com/Joao__Vitor27" class="button button-color-default">Twitter</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import {defineComponent} from 'vue';

export default defineComponent({
  name: 'MyPerfil',
  components: {}
});
</script>

<style scoped>
 .button-color-default {
   background-color: #021154;
   color: #fff;
 }
 .button-color-default:hover {
   background-color: #041f96;
   color: #fff;
 }

</style>
