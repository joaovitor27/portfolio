<template>
  <div class="columns">
    <div class="column is-6 is-offset-3">
      <div class="box">
        <div class="field">
          <label class="label">Nome</label>
          <div class="control">
            <input class="input" type="text" placeholder="Text input">
          </div>
        </div>

        <div class="field">
          <label class="label">Email</label>
          <div class="control has-icons-left">
            <input class="input" type="email" placeholder="Email input" value="">
            <span class="icon is-small is-left">
                  <i class="fas fa-envelope"></i>
                </span>
          </div>
        </div>

        <div class="field">
          <label class="label">Mensagem</label>
          <div class="control">
            <textarea class="textarea" placeholder="Textarea"></textarea>
          </div>
        </div>

        <div class="field is-grouped has-text-centered is-right">
          <div class="control">
            <button class="button is-link is-normal"><span class="icon">
                    <i class="fas fa-envelope"></i>
                  </span>
              <span>Enviar</span></button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import {defineComponent} from 'vue';

export default defineComponent({
  name: 'FormContact',
  components: {}
});
</script>

<style scoped>

</style>
