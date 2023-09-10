<template>
  <section class="section" id="resume">
    <div class="section-heading">
      <h3 class="title is-2">Resumo</h3>
      <h4 class="subtitle is-5">Meu currÍculo em PDF</h4>
      <button @click="generateDownloadLink" class="button button-color-default is-medium">
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
      link: require('@/assets/pdf/Currículo João Vitor da Silva Monteiro.pdf'),
    }
  },
  methods: {
    generateDownloadLink() {
      fetch(this.link.default)
          .then(response => {
            return response.blob()
          })
          .then(blob => {
            const url = window.URL.createObjectURL(new Blob([blob]));
            const link = document.createElement('a');
            link.href = url;
            link.setAttribute('download', 'Currículo João Vitor da Silva Monteiro.pdf');
            document.body.appendChild(link);
            link.click();
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
.button-color-default {
  background-color: #021154;
  color: #fff;
}

.button-color-default:hover {
  background-color: #041f96;
  color: #fff;
}

</style>
