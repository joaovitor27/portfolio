<template>
  <div class="column">
    <div class="card">
      <div class="card-content">
        <h3 class="title is-4">Perfil</h3>

        <div class="content">
          <table class="table-profile">
            <tr>
              <th colspan="1"></th>
              <th colspan="2"></th>
            </tr>
            <tr>
              <td>Endereço:</td>
              <td>Rua Quinze, Nº 5628, Santa Maria</td>
            </tr>
            <tr>
              <td>Telefone:</td>
              <td>(86) 9 9588-0950</td>
            </tr>
            <tr>
              <td>Email:</td>
              <td>joaovitor.monteiro.188@gmail.com</td>
            </tr>
          </table>
        </div>
        <br>
        <div class="buttons has-addons is-centered">
          <a href="https://github.com/joaovitor27" class="button is-dark">Github</a>
          <a href="https://www.linkedin.com/in/jo%C3%A3o-vitor-monteiro-577a49196/"
             class="button is-dark">LinkedIn</a>
          <a href="https://twitter.com/Joao__Vitor27" class="button is-dark">Twitter</a>
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

</style>
