<template>
  <section class="section" id="resume">
    <div class="section-heading">
      <h3 class="title is-2">Resumo</h3>
      <h4 class="subtitle is-5">Meu currÍculo em PDF</h4>
      <button @click="generateDownloadLink" class="button is-link is-medium">
        <span class="icon">
          <i class="fas fa-file-alt"></i>
        </span>
        <span>Download</span>
      </button>
    </div>
  </section>
</template>

<script lang="ts">
import {defineComponent} from 'vue';

export default defineComponent({
  name: 'SectionMyResume',
  components: {},
  data() {
    return {
      link: require('@/assets/curriculo_joao_vitor_da_silva_monteiro.pdf'),
    }
  },
  methods: {
    generateDownloadLink() {
      console.log(this.link);
      fetch(this.link.default)
          .then(response => {
            return response.blob()
          })
          .then(blob => {
            // Cria um objeto URL temporário para o blob
            const url = window.URL.createObjectURL(new Blob([blob]));
            console.log(url);
            console.log(blob);
            // Cria um link temporário e define o URL do objeto
            const link = document.createElement('a');
            link.href = url;
            link.setAttribute('download', 'Currículo João Vitor da Silva Monteiro.pdf');

            // Adiciona o link ao documento e clica nele para iniciar o download
            document.body.appendChild(link);
            link.click();

            // Limpa o objeto URL e remove o link do documento
            window.URL.revokeObjectURL(url);
            document.body.removeChild(link);
          })
          .catch(error => {
            console.error('Erro ao baixar o PDF:', error);
          });
    }
  }
});
</script>

<style scoped>

</style>
